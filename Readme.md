# Let's Do It: World Cleanup Day! ♻️

Over 16M trash heroes have cleaned up more than 500 000 tonnes of trash in 100+ countries! 😃 

We are now building a World Cleanup mapping app and platform to scale up the movement and inspire the next 100s of Millions to join the World Cleanup Day on **15th of September 2018**.

Getting rid of trash once and for all will save lives, improve health & reduce costs. Let's do it!

![World Cleanup Day](https://www.letsdoitworld.org/wp-content/uploads/2017/04/header.png)
![World Cleanup Day](https://www.letsdoitworld.org/wp-content/uploads/2017/04/content.png)

## Watch the App video

<a href="https://www.youtube.com/watch?feature=player_embedded&v=YnPvOVzbQpA
" target="_blank"><img src="https://s3.eu-central-1.amazonaws.com/lets-do-it-world/world-cleanup-day-app-video.png" 
alt="Let's Do It: World Cleanup Day!" width="100%" border="0" /></a>

## Find how you can contribute 🔨
Thank you for considering contributing to World Cleanup Day Mobile App! See the [CONTRIBUTING.md](https://github.com/letsdoitworld/World-Cleanup-Day-Mobile-App/blob/master/CONTRIBUTING.md)

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/c41ee20872534ae4997ebfe24793429a)](https://www.codacy.com/app/krishaamer/World-Cleanup-Day-Mobile-App?utm_source=github.com&utm_medium=referral&utm_content=letsdoitworld/World-Cleanup-Day-Mobile-App&utm_campaign=badger)
[![Code Climate](https://lima.codeclimate.com/github/letsdoitworld/World-Cleanup-Day-Mobile-App/badges/gpa.svg)](https://lima.codeclimate.com/github/letsdoitworld/World-Cleanup-Day-Mobile-App)
[![CodeFactor](https://www.codefactor.io/repository/github/letsdoitworld/world-cleanup-day-mobile-app/badge)](https://www.codefactor.io/repository/github/letsdoitworld/world-cleanup-day-mobile-app)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/c41ee20872534ae4997ebfe24793429a)](https://www.codacy.com/app/krishaamer/World-Cleanup-Day-Mobile-App?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=letsdoitworld/World-Cleanup-Day-Mobile-App&amp;utm_campaign=Badge_Grade)

## Roadmap 🗺️
This is a high-level roadmap for the next 6 months. For more details, please <a href="mailto:kristiina@letsdoitworld.org">request access to</a> the World Cleanup Day Asana.

### Phase 0: Design (April 1st):
- [ ] Update visual design to reflect World Cleanup Day brand

### Phase 1: (May 1st):
- [ ] User profile. User must authenticate through Facebook account or email address. Email address will be validated upon signing up.
- [ ] Type of users/roles. 
  - [ ] Master Admin/World Wide User Admin
  - [ ] Area Admin
  - [ ] Volunteer
  - [ ] * Waste management and sanitation operators
- [ ] Pile CRUD. Details about a pile fields, statuses and CRUD actions
  - [ ] Fields
  - [ ] Actions
  - [ ] Status

- [ ] Pile Comments
  - [ ] Any admin area can comment a pile added by any volunteer in his area. 
  - [ ] Comments can be deleted only by volunteer who added it or the admin area.

- [ ] View piles
  - [ ] In mobile: [my trash points](https://preview.uxpin.com/001ea6feee9ab2ec6731db74ccbc587f46cde1e3#/pages/65373808/simulate/sitemap)

Any user can view **on the web**  piles by selecting a layer or multiple options/filters in a new layer:

Important ones shown by two layers (template):
- [ ] I want to map:
  - [ ] by status pending (just inserted by users)
  - [ ] by status reported (if we have a protocol to report piles to local authorities for cleanup)
  - [ ] by user (filter piles inserted or allocated by the user)
  - [ ] by status confirmed (if we validated the pile - validation protocol)
  - [ ] by status unconfirmed (if we need and extra validation protocol)
  
- [ ] I want to clean
  - [ ] by status cleaned
  - [ ] by status allocated (fully allocated or partial allocated)
  - [ ] by status unallocated
  - [ ] by user (filter piles inserted or allocated by the user)
  - [ ] by team (filter piles inserted or allocated by team the user is member of)
  
- [ ] Optional ones(by selecting from advanced submenu you can choose different filters):.
  - [ ] Layer for sanitations operators to see the GPS location of the bags left by volunteers
  - [ ] Heat map layer
  - [ ] By date (last week, last month, custom range)
  
Each user will see by defaul all piles from the country where he is located by GPS, but if he want to see all piles from the world he will have this option (optimization for maps api calls)

- [ ] Help, Terms& conditions, Privacy, Contact us
- [ ] Feedback, warnings and errors

Every time when user will click Save, the user will receive feedback on the record, if the record was saved or was error, if there is no connection to the internet or GPS.
- [ ] Feedback
- [ ] Warnings
- [ ] Errors

### Phase 2: (June 1st):
- [ ] Reports
- [ ] Dashboard screen
- [ ] Type of user - Waste management and sanitation operators
- [ ] Pile PDF Export
- [ ] Notifications

### Phase 3: (August 1st):
- [ ] Team Cleanup management
- [ ] Predefined data


## Install steps ⚙️

1. Install bower plugins :  `bower install`
2. Install npm dependencies :  `[sudo] npm install`
3. Compile SASS and move files: `gulp`
4. Restore Plugins with the command `ionic state restore`
5. Add platforms:  `ionic platform add ios|android`
6. Build project:  `ionic build [ios|android]`
7. IOS/Android setup: change variable isIos AppConfig.js depending on platform
8. Copy www folder to project, without building:  `ionic prepare [ios|android]`

## Running the app

To run the app in the browser : `ionic serve`

## Contact :mailbox:
Join the movement and let's clean up the World together!

* Facebook: https://www.facebook.com/letsdoitworld
* Twitter: https://twitter.com/letsdoitworld
* Instagram: https://www.instagram.com/letsdoitworld/
* YouTube: https://www.youtube.com/letsdoitworld
* Flickr: https://www.flickr.com/letsdoitworld/
* Wikipedia: https://en.wikipedia.org/wiki/Let%27s_Do_It!_World
* Homepage: https://www.letsdoitworld.org/

## License

[GPL-3.0 license](https://opensource.org/licenses/GPL-3.0)
