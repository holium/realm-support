# Realm support

We are going to keep track of issues via this Github repo. 

If you come across any issues while using Realm, please post details [here](https://github.com/holium/realm-support/issues/new/choose).

## App issues

If you have an issue with an app supported by Holium, click below to post details:

- [Engram](https://github.com/holium/engram/issues)
- [Campfire](https://github.com/holium/campfire)

## Changelog

### `v0.0.78` - 01/06/23
* package.json fix typo `lib/rooom` -> `lib/room` by @niblyx-malnus
* forcing email fix by @drunkplato
* fix for incorrect error message and incorrect account id check by @drunkplato
* fix for incorrect error message and incorrect account id check by @drunkplato

### `v0.0.77` - 01/05/23
* better states in RemotePeer by @drunkplato
* 01-05-22 nightly update by @drunkplato
    * more rooms fixes
    * logout now cleans up rooms properly
    * cleaning handshake logic for latency situations

### `v0.0.76` - 01/04/23
* Open image attachment from DMs by @gdbroman
* Session load fix by @lodlev-migdev
   * if onboarding complete AND non production build, will auto login user
   * if onboarding NOT complete, will pickup where user left off
   * if production build and onboarding complete, will force user to login
* Fixes bug where app theme gets mixed up when switching between spaces by @leowini
* changed workspace build script by @drunkplato
* improvements to rooms stuff, fix #636 bug by @Tenari
* Rooms lib state cleanup by @drunkplato
* 01-04-23 nightly updates by @drunkplato

https://user-images.githubusercontent.com/29574724/210394049-893f004f-824c-40f6-9105-1cc0cc76352d.mov


### `v0.0.75` - 01/03/23
* fixed room connection edge case by @drunkplato
* rooms connection fixes by @drunkplato
    * solves some edge cases around latency and the ready signal

### `v0.0.74` - 01/02/23
* fix to ignore existing email error. will resend verification code if … by @lodlev-migdev
   * If account exists with email entered, send verification code and allow user to onboard again.
* Notification dot on rooms chat icon by @gdbroman
* Fix selectedSpace.type error by @gdbroman
     * Remove the non-null assertion.
     * Add a null check.
     * Also fix EmptyPicture's prop types
* Fix devtools for some webview types by @sethfork
* 01-02-2023 nightly update by @drunkplato

https://user-images.githubusercontent.com/29574724/210133606-c6d61213-fa6b-4ef0-80cb-0673bf9fb2a3.mov



### `v0.0.73` - 12/30/22
* Dynamic DM input height with shift-enter by @gdbroman
* Invert PassportCard when close to bottom of screen by @gdbroman
* 12-30-22 daily update by @drunkplato
   * multi-line dm input fixed
   * fix for PassportCard orientation and bottom of page

https://user-images.githubusercontent.com/29574724/209992072-116c49b1-1989-4ed9-8ab6-08c834ed1342.mov

https://user-images.githubusercontent.com/29574724/210103671-9fda142c-3750-404a-a665-66ed2839847a.mov

### `v0.0.72` - 12/29/22
* Fix AppSearchPopover positioning by @gdbroman
* 581 disconnect from all peer audio when you leave a room by @drunkplato
* App search and rooms hangup fixes by @drunkplato

https://user-images.githubusercontent.com/29574724/209835734-28833931-a103-420c-9260-ae1ec94ffdb6.mov

### `v0.0.71` - 12/29/22
* Fix: basic profile photo crash + many new components in design-system by @drunkplato

### `v0.0.70` - 12/28/22
* Fix: context menu closes on item click by @gdbroman

### `v0.0.69` - 12/27/22
* Fix: selection causing renderer to hang by @gdbroman 

### `v0.0.68` - 12/26/22
* Further context menu improvements by @gdbroman
* addded more fixes for the groups styles.. moving on for now by @drunkplato
* Rooms enter exit sound by @drunkplato
* Subscription channel status in settings by @gdbroman
* context menu updates, room enter/exit sound, group theme improvements, etc. by @drunkplato


https://user-images.githubusercontent.com/29574724/209474584-56954b01-a055-4439-a40e-611c81712d91.mov

https://user-images.githubusercontent.com/29574724/209437708-a66501d4-f2d9-469f-aa73-a6164adecb0c.mov

### `v0.0.67` - 12/23/22
* unsubscribe from all providers on %set-provider by @leowini 
* leaving correct path by @leowini 
* 403 error by @lodlev-migdev
* open relic browser from webview links. also has group and talk theme … by @drunkplato 
* groups theme injection, open relic links from groups, tlon.network fix by @drunkplato 

https://user-images.githubusercontent.com/6413077/209399534-0c735b5b-b6ee-4fa5-8b36-b17b21feee06.mov

### `v0.0.66` - 12/22/22
- bazaar app install fixes
- bazaar app host is set properly
- added a number badge to the rooms button so people can see if there is anyone in a room at a glance.
- When a ship is added to space -> ship is added to group and receives an invite for that group.
- When a ship is added to space -> ship receives an invite to the space. May want to refactor spaces so that a ship can simultaneously be added to a space and invited to the space (in %groups ship doesn't actually have to accept before being added as a member).
- Fixes issue where app catalog entries are not shared properly on joined-bazaar.
- Fixes install statuses to emulate the pre-OTA stable install process
- Fixes issue with host being an empty unit.
     - adds poke to manually set a host if a null unit is present
- Sync %spaces and %groups members by @leowini
- Fix context menu overflowing near bottom of screen by @gdbroman

Before | After
--- | ---
<img width="452" alt="Screenshot 2022-12-22 at 2 38 24 PM" src="https://user-images.githubusercontent.com/29574724/209146168-16260777-5ca5-4116-8646-c3afec7135c4.png"> | <img width="452" alt="Screenshot 2022-12-22 at 2 36 39 PM" src="https://user-images.githubusercontent.com/29574724/209146296-229cb034-38c6-47ee-ba4b-76dbcbc52f47.png">

### `v0.0.65` - 12/21/22
- Fix the "Cannot construct URL" error
- Update toolbar URL when navigating through links
- Fix the search button
- Make search input non-draggable
- Enable IP addresses

https://user-images.githubusercontent.com/29574724/208787076-7ba94a3b-9284-4124-9720-72bc7af84a83.mov

### `v0.0.64` - 12/20/22
- added bulletin agent to the realm desk which allows for us to push featured spaces and other listings
- dm double send fix
- dm update fixes

### `v0.0.63` - 12/17/22
- onboarding fixes

### `v0.0.62` - 12/16/22
- fix for stall update crashing on recommend and app suite add
- check if groups 2 is installed prior to allowing Realm install (need groups 2 for Realm messaging and is proxy for 417 zuse being updated)
- fixed pinned apps updating
- dynamic height fixed in room chat with 5+ people
- disables onboarding button while"Install Realm" is running
- mark agents as preinstalled and skip "Install Realm" step if hosted
- cap rooms to max capacity

### `v0.0.61` - 12/15/22
- better image parsing for space creation detail step
- edit detail image fix
- member list rendering fix
- Tooltip overflow scrollbar removed 
- minor scrollbar style improvements
- removed unneeded styles from MiniAppWindow
- bazaar unrecommended fix

### `v0.0.60` - 12/14/22
- minor bazaar fixes around recommended apps

### `v0.0.59` - 12/14/22
- fixes scrollbars appearing everywhere and applies a style to the scrollbars that do exist.
- fixes a bug in the rooms lib that prevented properly cleaning up WebRTC peer connections when a room was deleted.

### `v0.0.58` - 12/13/22
- disable next button on the Install Realm step while the loader is visible
- disable click on spaces selector while it is in it's loading state
- fixes bazaar recommended app bug in spaces. If someone didn't have a catalog entry for an app when it was recommended, they could experience a crash when clicking on the home button on the spaces home screen.
- disable check for update that causes 404 errors for users during a new build deployment (for now users manually must check for updates or it will check when the app is opened).
