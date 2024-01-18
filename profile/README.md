# Aquamarine

## Q&A

### What is Aquamarine?
Aquamarine is a Miiverse Revival project aiming to capture the essence of Miiverse (UI Design, General Charm, etc), while giving it newer and modern features.

### How do I install Aquamarine?
Currently Aquamarine is in development, so no builds are avaliable to the general public yet. Periodically, we may have open betas, that allow people to come in and test certain functions.

### How can I follow Aquamarine's development?
You can join the discord and get development updates.

https://discord.gg/s5FEBBkwAn

### How come the game/app *insert name here* doesn't work as intended!
Some applications use something called app data. App Data is a string coded into most communities that allow games to communicate with them. Most of these strings have not been found by data-miners or reverse engineerers. If/when those strings are found, we'll be sure to implement them into our API. Another factor that could affect games is patches, as some games had Miiverse completely patched out of them in an update.

### What about Pretendo?
Pretendo is a seperate revival service that revives Miiverse, as well as most other online services for the Wii U and 3DS. Aquamarine only revives Miiverse.

## Completion

So far, here's a comprehensive list of everything that is working

### Portal (Wii U Interface)

- [x] Basic community loading
- [x] Basic post loading and viewing
- [ ] User page
- [ ] Post sorting (Topic Tag, Popular Posts, Time Created, Yeahed Posts)
- [ ] User customization
- [ ] Account reloading (Fetching new Mii Info, Mii Name, etc)
- [x] Account Creation
- [ ] Account Creation rules page (Miiverse Manners)
- [ ] Activity Feed
- [ ] Messages
- [ ] Notifications
- [ ] My Menu
- [ ] Settings
- [ ] Blocking and reporting
- [x] Community Type Viewing (Announcement, Sub Community, Main Community, Normal Community)
- [ ] Posting via Applet
- [ ] Screenshot taking

### CTR (3DS Interface)
- [x] Basic community loading
- [x] Basic post loading and viewing
- [ ] User page
- [x] Post sorting (Topic Tag, Yeahed Posts)
- [ ] User customization
- [ ] Account reloading (Fetching new Mii Info, Mii Name, etc)
- [x] Account Creation
- [ ] Account Creation rules page (Miiverse Manners)
- [ ] Activity Feed
- [ ] Messages
- [ ] Notifications
- [ ] My Menu
- [ ] Settings
- [ ] Blocking and reporting
- [ ] Community Type Viewing (Announcement, Sub Community, Main Community, Normal Community)
- [x] Posting via Applet
- [ ] Screenshot taking

### API
- [x] POST v1/posts (Posting to a community)
- [x] POST v1/posts/xx/empathies (Creating a "Yeah!")
- [x] GET v1/communities (Grabbing sub communities)
- [x] POST v1/communities/favorite (Favoriting communities)
- [ ] GET v1/notifications (Notifications for games to pull from)
- [ ] GET v1/people (Friends that appear on your Wii U menu in orange pants)
- [x] POST v1/people (Creating a new user)
- [ ] GET v1/topics (Wara Wara Plaza)
- [ ] POST v1/friend_messages (In-game messaging)
