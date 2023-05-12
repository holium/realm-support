# Realm support

We are going to keep track of issues via this Github repo. 

If you come across any issues while using Realm, please post details [here](https://github.com/holium/realm-support/issues/new/choose).

## App issues

If you have an issue with an app supported by Holium, click below to post details:

- [Engram](https://github.com/holium/engram/issues)
- [Campfire](https://github.com/holium/campfire)

## Changelog

### `0.10.11-hotfix` - 05/12/23

* Add metadata to hosting.holium.com by @gdbroman 
* Unique index bookmarks_path_url by @gdbroman 
* Cookie partition and dock sql join fix by @drunkplato 
* remove scry on init by @ajlamarc 

### `0.10.10-hotfix` - 05/12/23

* Theming changes by @ajlamarc 


![Screenshot from 2023-05-10 20-20-13](https://github.com/holium/realm/assets/56094073/a807d0fe-a67b-44e2-b700-fdfae32c2860)
![Screenshot from 2023-05-10 20-20-30](https://github.com/holium/realm/assets/56094073/e6bd87ed-b9dd-4d19-8f60-06950957f73d)


* Fix wallpaper loading for holium.com by @gdbroman 
* Only preload wallpapers on demand by @gdbroman
* Static landingpage for mobile by @gdbroman 
* fix RE-112: show user-friendly error message in chat when deleting a … by @Tenari

<img width="442" alt="image" src="https://github.com/holium/realm/assets/3653835/19206b21-4631-4a98-947f-2f3a17a94931">

* fix RE-89: close modal when photo is set, dont show two photos at once by @Tenari 
* App install updates volatile state by @drunkplato 
* add symlink to json.hoon from urbit/base-dev by @lodlev-migdev 
* ensure PR has build label else do not run build steps by @lodlev-migdev 
* prevent duplicate/multiple clicks on all auto update forms by @lodlev-migdev 
* fix windows build by @lodlev-migdev 
 * Ensure Windows signed .EXE is moved to droplet then ultimately to Github Release.
* fix by @ajlamarc 
* Update website theme when switching space by @gdbroman 

https://github.com/holium/realm/assets/29574724/6a6b7622-0c3d-412e-aeb9-156136ee866e

* Update ghproxy download links by @gdbroman 
* rename all ghproxy.holium.xyz references to download.holium.com by @lodlev-migdev
* Local progressive web app support by @gdbroman

https://github.com/holium/realm/assets/29574724/8cb825cc-2f65-406c-af80-9340784aff5a

### `0.10.9-hotfix` - 05/10/23

* bazaar treaty case data type fix by @lodlev-migdev
* fix RE-107: exclude %invited people from memberCount by @Tenari 
* make AppTile open/unfocused bubbles appear -> fix RE-27 by @Tenari 
* fix RE-92: use smarter/better isAdmin() call by @Tenari
* fix RE-54: don't use index as part of react-key, since we only allow … by @Tenari
* update commit by @ajlamarc
* Remove old lib files by @ajlamarc

### `0.10.8-hotfix` - 05/09/23

* Re 47 rooms node server by @drunkplato

### `0.10.7-hotfix` - 05/09/23

* New holium.com by @gdbroman
* 413 updates by @ajlamarc
* fix spaces permissions by @Tenari
* Custom titlebar by @gdbroman 
* Move installation step before passport by @gdbroman 

https://user-images.githubusercontent.com/29574724/236953024-65a0c102-7771-4392-ac5c-348d8891498b.mp4

* When joining a space, the stall data doesn't get refresh in UI until logout/login by @drunkplato 
* Photoswipe fix by @gdbroman

### `0.10.6-hotfix` - 05/05/23

* Fix framer-motion animation by reverting version by @gdbroman

### `0.10.5-hotfix` - 05/05/23

* Remove residual server codes from createAccount by @gdbroman
* Buy Server btn by @gdbroman

https://user-images.githubusercontent.com/29574724/236482694-7690e5ef-96e2-42e5-8a76-1bf606849b69.mp4

* Showpassword for login & create account by @gdbroman 

# Web

https://user-images.githubusercontent.com/29574724/236497891-486e84cb-9d40-451d-8357-b0c44c8c4027.mp4

# Desktop

https://user-images.githubusercontent.com/29574724/236498290-f7d0976e-4218-41ab-925f-a378b5864450.mp4

* bowl passing again by @Tenari 
* fix command by @ajlamarc 
* Init holium com dir by @gdbroman
* Move holium.com into monorepo by @gdbroman 
* Test JIRA automation by @ajlamarc
* Update issue templates by @ajlamarc
* Bump http-cache-semantics from 4.1.0 to 4.1.1 by @dependabot 
* update year by @ajlamarc 

### `0.10.4-hotfix` - 05/04/23

* #1549 fix pinning/unpinning chats in Inbox by @Tenari
* fixes #1476 by @Tenari
* pass bowl so we arent defaulting to ~zod nil 0 by @Tenari
* removed serverCode from auth.db by @drunkplato
* Get Realm page by @gdbroman

### `0.10.3-hotfix` - 05/04/23

* Use Node's inbuilt fetch instead of cross-fetch by @gdbroman

### `0.10.2-hotfix` - 05/03/23

* Sentry for hosting by @gdbroman 
* Add missing sentry.edge.config.ts by @gdbroman 
* fix emails parsing as link in chat ui fragment-parser by @Tenari 
* Add timeout to onboarding network requests by @gdbroman
* handle decentralized occasional slow delivery by using received_at as… by @Tenari
* Refactor schemas and column names to be based on constants by @drunkplato 
* #1396 better push notif msg by @Tenari 
* Fix onboarding unrecoverable state bc of persisted step by @gdbroman
* handle case where agent doesn't do received-at yet gracefully by @Tenari

### `0.10.1-hotfix` - 05/03/23

* Spaces permission and initial stall fixes by @drunkplato
* Bubble width adjustment by @drunkplato
* Passport and installation fixes by @drunkplato 
* Remove "Already have an account?" from claim flow by @gdbroman

### `v0.10.0` - 05/02/23

* Granular `@holium/design-system` exports for tree-shaking by @gdbroman
* Rm not yet added dialog by @gdbroman
* Update %realm desk.ship to ~hostyv instead of ~zod by @bacwyls
* Symlink base-dev by @ajlamarc
* #1372 lastMessage preview in inbox looks better by @Tenari
* #1372 fix the reply message missing crashes chat problem, and upgrade… by @Tenari
* #1372 copy options based on message contents by @Tenari
* fixes artifact naming for windows builds by @lodlev-migdev
* Rm package-lock and update yarn.lock by @gdbroman
* Docs updates by @ajlamarc
* bazaar and spaces in rebuild by @drunkplato
* add step to init submodule first by @ajlamarc
* add urbit submodule by @ajlamarc
* New claim flow (Onboarding) by @gdbroman
# Claim invite code page

![CleanShot 2023-04-05 at 17 17 40@2x](https://user-images.githubusercontent.com/29574724/230126298-ccab2f58-1731-4a16-ab69-981fe7e4056e.png)

# Download Realm page (when no ships)

The "Get Hosting" menu item takes you to the "Choose ID" part of the onboarding flow.

![CleanShot 2023-04-05 at 17 18 05@2x](https://user-images.githubusercontent.com/29574724/230126401-1b3916e3-b6c8-4f7f-86a1-eb1eecd8649b.png)

* Onboarding cleanups by @gdbroman
 * Fix font-family being unset for some components
 * HoliumButton should redirect back to holium.com
 * Remove onBack from CredentialsDialog
 * Fix flickering of account dialogs

https://user-images.githubusercontent.com/29574724/232246903-89287b10-3150-48b4-b3b4-8cda7f85f011.mp4

* Rebuilt os process bazaar by @drunkplato
* #1374 make media type regexes case insensitive for weird systems that… by @Tenari
* #1372 both members of realm-chat %dm type can edit path info by @Tenari
* Clear ephemeral chat after toggle off by @gdbroman

https://user-images.githubusercontent.com/29574724/232096144-3efeef62-ff02-4496-b8e3-138c0b2bb039.mp4

* Remove %courier subscription status in Settings by @gdbroman

Before | After
--- | ---
![CleanShot 2023-04-14 at 18 33 38@2x](https://user-images.githubusercontent.com/29574724/232104242-43e986ad-b845-4b93-b822-947bf421aef5.png) | ![CleanShot 2023-04-14 at 18 34 56@2x](https://user-images.githubusercontent.com/29574724/232104255-60cc594d-3eb9-4ef8-83a0-27551022969e.png)

* Enable dragging & resizing of Realm in windowed mode by @gdbroman

https://user-images.githubusercontent.com/29574724/232107605-d2913d5f-37d7-47f2-af6d-031b29c13ea3.mp4

* Consolidate home pane by @ajlamarc
 * Compress comet names as well as moons in friends list: 
 
 ![image](https://user-images.githubusercontent.com/56094073/232256746-26df3c73-ba7c-4595-bd34-816d47097ea7.png)

* Rebuilt os process final pass by @drunkplato
* comparing changes by @drunkplato
* Add missing Download links for claim flow by @gdbroman
* #1366 jump to index when clicking notifrow for chat, and also dismiss by @Tenari
* #1366 jump to index when clicking notifrow for chat, and also dismiss by @drunkplato
* splash screen is integrated with style updates by @drunkplato
* move conduit to os/services/api by @ajlamarc
* new convenience scry for getting all updates since a timestamp for each table by @Tenari
* #1372 reply fragments will show the preview version of all fragments,… by @Tenari
* Rebuilt os process tests refactor by @ajlamarc
* dns resolution for ipv6 on macOS and node >= 18 seems to be broken; prefer ipv4 by @Tenari
* New Realm onboarding by @gdbroman
* #1372 reorder chat inbox when new messages come in, and when you go b… by @Tenari
* #1372 deleting a chat also sends pokes to delete notifs in notif-db by @Tenari
* #1459 client and hoon side update to change json interface for chat-db by @Tenari
* Resubscribe on channel when quit event received by @leowini
* #1444 fix editing convertFragmentsToText function by @Tenari
* Bazaar fixes by @lodlev-migdev
* #1372 emoji picker in chatInput, using %custom content type to send a… by @Tenari
* #1372 properly grow row heigh when reactions come in by @Tenari
* #1372 allow soundcloud to play by @Tenari
* Revert "#1372 emoji picker in chatInput, using %custom content type to send a…" by @drunkplato
* Onboarding hangs, cookie not set issues by @leowini
 * Fixed an async bug where the conduit is initialized before receiving the cookie.
 * Fixed a crash from a bad set-contact poke
 * Fixed a hang caused by a missing parameter in the createAccount call

* Web onboarding fixes by @gdbroman
* Favicon for hosting.holium.com by @gdbroman
* Redirect to `/account/download-realm` on login if no ships by @gdbroman
* Apply filter to onboarding bg by @gdbroman 
* Rebuilt os process by @drunkplato
* Fix inputs not using --rlm-font by @gdbroman
* Fix ESLint errors from `rebuilt-os-process` by @leowini
* Rebuild os process sort imports by @ajlamarc
* Small chat fixes by @drunkplato
* miscellaneous fixes by @Tenari
* Onboarding adjustments by @gdbroman
* Fix introduced CI errors by @gdbroman
* More onboarding and style cleanups by @gdbroman
* Fix import sort for @holium packages by @gdbroman
* #1481 when a user adds a ship, it should update the Authstore by @Tenari
* add USE_HARD_LINKS=false for build to get beyond symlink issues when … by @lodlev-migdev
* bazaar fixes for Friday by @lodlev-migdev
 * pinned, unpinned, and reorder fixes
 * modified sqlite schema by removing dockIndex and simply storing json array in correct order (if you think we need dockIndex for whatever reason (future   proof), let me know and I can add it back. after table refactor, it was no longer required
 * modified bazaar (agent/hoon) to %give %dock-update gifts as updates when the dock changes due to a pin/unpin or reorder action

* Rebuilding wallet for the os refactor by @leowini
* various rebuild todo fixes by @Tenari
* wait for Realm installation by @lodlev-migdev
* BUILD_VERSION set in main process environment by @lodlev-migdev
* Realm install fix by @lodlev-migdev
* Fix RealmInstallStatus imports by @gdbroman
* Settings & Account Management by @gdbroman 
* Fix onboard build error & power off btn styling by @gdbroman 
* Populate passport card in settings with %friends data by @gdbroman 
* Rebuilt rooms 2023 by @drunkplato
* Fix ESLint rooms errors by @gdbroman 
* Apply local fonts by @gdbroman 
* Rooms voice connection fixed by @drunkplato
* when a user opens a chat, hit the scry for the timestamp of the last … by @Tenari
* setting session cookie on login by @drunkplato
* Fix wallpaper settings by @gdbroman
* added basic amplitude tracking by @drunkplato 
* Simple account settings for self-hosted ships by @gdbroman 
* More granular settings tabs by @gdbroman
* inline edit style fix and moved chatdb sub to after scries by @drunkplato 
* Last-minute onboarding improvements by @gdbroman 
* Disable onBack when installing agent by @gdbroman
* Inital load fixes by @drunkplato 
* Fix forcedNextStep logic by @gdbroman 
* Remove unused password step by @gdbroman 
* Rm logs (to trigger prerelease) by @gdbroman 
* fixed create bug by @drunkplato 
* remove 'courier' agent from production build deployment by @lodlev-migdev 

### `0.9.5-hotfix` - 04/25/23

### `0.9.4-hotfix` - 04/24/23

* Revert "#1372 emoji picker in chatInput, using %custom content type to send a…" by @drunkplato

### `0.9.2-hotfix` - 04/17/23

* #1374 make media type regexes case insensitive for weird systems that… by @Tenari
* #1372 both members of realm-chat %dm type can edit path info by @Tenari
* Clear ephemeral chat after toggle off by @gdbroman 

https://user-images.githubusercontent.com/29574724/232096144-3efeef62-ff02-4496-b8e3-138c0b2bb039.mp4

* Remove %courier subscription status in Settings by @gdbroman

Before | After
--- | ---
![CleanShot 2023-04-14 at 18 33 38@2x](https://user-images.githubusercontent.com/29574724/232104242-43e986ad-b845-4b93-b822-947bf421aef5.png) | ![CleanShot 2023-04-14 at 18 34 56@2x](https://user-images.githubusercontent.com/29574724/232104255-60cc594d-3eb9-4ef8-83a0-27551022969e.png)

* Enable dragging & resizing of Realm in windowed mode by @gdbroman

https://user-images.githubusercontent.com/29574724/232107605-d2913d5f-37d7-47f2-af6d-031b29c13ea3.mp4

* Consolidate home pane by @ajlamarc
* #1366 jump to index when clicking notifrow for chat, and also dismiss by @drunkplato

### `0.9.1-hotfix` - 04/13/23

* Granular `@holium/design-system` exports for tree-shaking by @gdbroman
* Rm not yet added dialog by @gdbroman
* Update %realm desk.ship to ~hostyv instead of ~zod by @bacwyls
* Symlink base-dev by @ajlamarc
* #1372 lastMessage preview in inbox looks better by @Tenari
* #1372 fix the reply message missing crashes chat problem, and upgrade… by @Tenari
* #1372 copy options based on message contents by @Tenari

### `v0.9.0` - 04/10/23

* New chat and notification system is in
* Lots of bug fixes
* Realm chat by @Tenari
* Realm chat UI by @gdbroman
* #1034 %notif-db hoon agent by @Tenari
* Toggle component for settings by @drunkplato
* Integrate pin/unpin api by @drunkplato
* delete log fetches, applies, and inserts by @drunkplato
* New frag parser by @Tenari
* replies, editing, and reactions by @drunkplato
* Reply edit reactions by @drunkplato
* Blocks and media polish by @drunkplato
* Image upload and delete logs by @drunkplato
* Notif sql hookup by @drunkplato
* Status content type and timestamp by @Tenari
* attempting to fix style by @drunkplato
* Last message bug by @leowini
* del-log in notif-db by @Tenari
* Feature: New chat system by @drunkplato
* Show theme on lock screen by @ajlamarc
 * update lock screen theme on save from settings
 * update lock screen theme on each login
 * proper lock screen shows on boot and animates when changing between selected ships

https://user-images.githubusercontent.com/56094073/227800649-4796898e-c5b6-4524-a527-214ef08c7b74.mp4

* fix typo by @ajlamarc
* chat crash on re-open fix by @drunkplato
* uncommented something that may have broken build by @drunkplato
* prevent errors when/if needing to rerun a build and no new commits fo… by @lodlev-migdev
* Fix urbit-ob `.d.ts` declaration by @gdbroman
* make s3 handle people who configured the endpoint with ... by @Tenari
* enable close button by @ajlamarc
* Basic shutdown by @ajlamarc
 * Clicking power button closes the app
 * Clicking power button opens a modal that says "Realm will power off automatically in 60 seconds".  User can cancel, power off, or wait.
* Chat performance improvements by @drunkplato
* add gap between buttons by @ajlamarc
* only do one notif per message, and combine all the msg-parts to creat… by @Tenari
* reactions and emoji picker are more efficient and works by @drunkplato
 * Fixes the emoji picker closing when trying to search. 
 * memoized the reaction row which was causing a re-render on every click
* Add as friend adds to Friends by @leowini
* fixed reaction measurement and setting window.ship by @drunkplato
* Chat log scroll fix by @drunkplato
* committed in design-system folder... by @drunkplato
* Fix tsc errors to unstuck CI by @gdbroman
* Fix remaining --rlm-rgba variables by @gdbroman
* Clean up design system imports by @gdbroman
* editing fixes by @drunkplato
* #1298 Update the sentAt time via an interval similar to the clock by @Tenari
* Login error cleanup by @ajlamarc in https://github.com/holium/realm/pull/1287
* #1298 only match at beginning of input or after newline by @Tenari
* use same id on all the main elements of the Bubble for contextMenu purposes by @Tenari
* New Holium onboarding by @gdbroman
* #1298 fix delete group chat ui crash, re-do the growing chat input by @Tenari
* Opengraph pretty again by @Tenari
* Holium eventsource by @gdbroman
* Revert "Holium eventsource" by @drunkplato
* Fix smooth scrolling + add scroll on reply click by @gdbroman

https://user-images.githubusercontent.com/29574724/229910793-f74e4cde-58e9-4999-810a-d56ad5739346.mp4

* Fix: Relic browser greys out on search by @gdbroman 
* #1298 %status should be sent when the expiresDuration is changed by @Tenari
* #1298 clicking on an image shows it in a lightbox by @Tenari
* Fix electron-rebuild by @gdbroman
* Fix photoswipe global css  problem by @gdbroman
* #1298 shrink chat input after send, enable right click save image by @Tenari
* Always show scrollbar padding in WindowedList by @gdbroman
* Fixed rooms crash - prevents two rooms with same name by @leowini
* photoswipe.css by @gdbroman
* fix lightbox interaction with context menu by @Tenari
* Fix home panel icon colors by @gdbroman 
 * Clicking on members icon closes it now
 
 ![CleanShot 2023-04-07 at 23 00 06](https://user-images.githubusercontent.com/29574724/230678358-4759214d-4e7f-420e-96a9-acd1df161c93.gif)
 
* Local ErrorBoundries for Windows + TrayApps by @gdbroman
* Inject both hex and rgba color values by @gdbroman
* Spaces get their own realm chat by @Tenari
* Pass down selectedChatPath, cache chats, textarea not required by @ajlamarc
* Keep scrolled to bottom on image send by @gdbroman
* Fix multiplayer issues by @gdbroman
 * Fix ephemeral chat unintentially triggered in inputs
 * Fix chat triggered by backslash
 * Fix "ghost cursors"
  * This was already handled by listening to the LeftRoom event

https://user-images.githubusercontent.com/29574724/230605987-34f15aaa-f6cd-46f2-b241-abfe958b9679.mp4

* Final Chat TODO by @drunkplato
 * path flag for whether newly joined members get the chat history

<img width="401" alt="image" src="https://user-images.githubusercontent.com/6413077/220614082-2f29c900-6cd1-442c-9a56-567297d9a412.png">

* fix: special app 'done' handling ignored when running auto updates by @lodlev-migdev
* Fix chatlog load at bottom & cleanup by @drunkplato
* fixed several details by @drunkplato

### `v0.8.0` - 03/27/23

* Public facing README for @holium/design-system by @gdbroman
* Add contact info to our NPM libs by @gdbroman 
* Init `@holium/shared` by @gdbroman
* change glob and version by @ajlamarc
* Rooms present count quick fix by @leowini
* Remove `getComputedStyle` from `@holium/design-system` by @gdbroman
* Don't remove blur when home pane is open by @ajlamarc

### `v0.7.0` - 03/20/23

* Multiplayer + `lib/presence` by @gdbroman

https://user-images.githubusercontent.com/29574724/225707389-64d7fc24-feac-4ea9-a791-b6caf79cb393.mp4

  * Togglable "multiplayer" cursor streaming in Realm rooms (disabled by default).
    * With ephemeral chat invokable from anywhere (disappears after 5s).
  * A lightweight developer module, @holium/realm-presence.
    * Demo implementation in lib/presence/code.

- space path prevent duplicates
- rooms signaling limiter
* Ask for mic permissions when first opening tray app by @gdbroman
  * Mic tooltip in RoomsDock

https://user-images.githubusercontent.com/29574724/224502712-8a818e75-93e3-4f7d-adb7-596aec34d6d6.mov

![Screenshot 2023-03-11 at 11 08 56](https://user-images.githubusercontent.com/29574724/224502084-6390d170-b428-4460-8dc5-46b11e3f5b52.jpg)

- translucent bg for apps integrating with Realm's theme system
* add back space name by @ajlamarc 
* create a sentry release (with source maps) when running staging build… by @lodlev-migdev
* Added invite member updates for %groups sync by @leowini
* Remove all non-null assertions by @gdbroman 
* Rooms signal fix by @leowini 
* Fixed initial update in DiskStore by @leowini
* 995 device ipc sleep wake by @Tenari
* Rm logs in main by @gdbroman
* Added code signing using EV code signing certificate for staging build by @lodlev-migdev 
* EV code signing enabled for Windows build by @lodlev-migdev
* Do not build when do-not-build label is set on a PR by @lodlev-migdev
* Rename multiplayer to presence by @gdbroman 
* build Sentry pipeline with debug enabled by @lodlev-migdev 
* Nuke rooms state by @leowini
* fix #1215 by @Tenari

* To understand how the presence lib works, see `lib/presence/README.md`._

* Presence git ignore by @gdbroman
* #1036 make spaces paths communicated in a url-safe manner by @Tenari
* style fix by @drunkplato
* Remove AppWindow BG by @drunkplato
  * removes the default theme window color as the bg so we can have apps layer on the transparent window


### `v0.6.0` - 03/04/23

* fixing audiowave animation bug by @drunkplato
* Properly disable Next btn on error in InstallAgent dialog by @gdbroman
* Moving a bunch of components to design system by @gdbroman
* Fix preconstruct error (type export) by @gdbroman
* Enforce type-only exports by @gdbroman
* Make window resizing snappy by @gdbroman
   * Make all window corners resizable
   * Keep mouse in resize state when dragging
   * Disable double click in Relic input field
   * Use IPC'd mouse coordinates (this makes dragging + resizing work over webviews, and it's snappier)
  
  #### Custom mouse

https://user-images.githubusercontent.com/29574724/221646771-43a390d3-8963-43fb-98ba-ed6ae1e21db6.mov

  #### Default mouse

https://user-images.githubusercontent.com/29574724/221807232-37556280-6483-4e6b-b23d-125d04cbdf3f.mov
 
* Filtering out groups that are already spaces by @leowini
* Rooms: make test-ui ShipConfig a gitignored file with example by @gdbroman
* Fix: can't reference realm-room from inside realm-room by @gdbroman
* Rename test-ui to test-ui-vite by @gdbroman
* Unify ships.json name with README by @gdbroman
* Fix rooms/test-ui ships.json name by @gdbroman
* Fix undefined ships.json by fetching it from public by @gdbroman
* Fix default cursor disappearing on misc elements by @gdbroman
* Stabilize Relic webview handling by @gdbroman
* Fixed can't kick a dead member bug by @leowini
* Fix room/test-ui (add back observers) by @gdbroman
* #1177 don't update current space from /updates subscription by @Tenari

### `hotfix v0.5.1` - 02/25/23
* fixing audiowave animation bug by @drunkplato
* Linux release channel by @lodlev-migdev
* Switch to production download channel in settings (needs Select upgrade)  by @lodlev-migdev

### `v0.5.0` - 02/23/23

* Save the currently opened space in %spaces by @ajlamarc
* rooms relic fix & copy spaces path by @drunkplato
* Add back missing "Start" text for create room btn by @gdbroman 
* Fix mouse invisible on Windows/Linux by @gdbroman
* 185 auto update progress by @lodlev-migdev
* Tray app component by @drunkplato
* TrayApp positioning fix by @drunkplato 
* 941 contact sharing realm by @leowini 
* Fix docked app status indicator and more by @gdbroman

https://user-images.githubusercontent.com/29574724/218250878-ad6d3328-b799-44a0-86d5-3a79e5bef993.mov

* Cleaning up Window & Titlebar components by @gdbroman 
  * Clean up Window and Titlebar component abstractions, types, and file names
  * Enable bottom-left window resizing
  * Style windows w/ 90% opacity and blur

https://user-images.githubusercontent.com/29574724/218436345-2e32ea58-045a-459c-9430-83f05b5e5170.mov

* fixed wallet back button on onboarding and removed verb logs from agent by @drunkplato 
* Filter out null previews so ContactRow doesn't crash by @gdbroman
* Fix app links not being opened in relic by @gdbroman
* Edit member role set by @leowini 
* support for linux builds by @lodlev-migdev
* fix for account recovery via email address and printing better error … by @lodlev-migdev 
* Use default cursor on Linux by @gdbroman 
* fixed bug where the Add Ship feature was not installing Realm due to … by @lodlev-migdev 
* System settings - Interface - Isolation Mode by @gdbroman 
* 644 speaking detection by @drunkplato
* Fix crash on pressing `esc` for dialogs by @gdbroman 

### `v0.4.0` - 02/13/23
This release contains: 
- the new mouse and window system refactor which will improve performance overall and prepares for multiplayer mode. 
- new app updater with autoupdate logic 
- contact sharing is now fully handled by Realm
- windows build updater and fixes
- tray app system is revamped 
* Move mouse to its own layer by @gdbroman
* App update progress by @lodlev-migdev
* Added link to update server source by @lodlev-migdev
* fixed up a few things so changes will run in 'production' build by @lodlev-migdev
* set --clobber flag on 'gh release upload command' by @lodlev-migdev 
* fixes for dev vs prod build by @lodlev-migdev
* Fix setWindowButtonVisibility undefined on Linux/Windows by @gdbroman 
* 892 new chat components by @drunkplato 
* #926 choose urbit by @lodlev-migdev 
* Frontend style guide by @gdbroman 
* Enable tsc in CI by @gdbroman 
* Fix rooms by @gdbroman 
* Clean up remaining unnamed observer components by @gdbroman 
* Fix mouse invisible on Windows/Linux by @gdbroman 
* Add prerelease caveat in README by @gdbroman 
* 185 auto update progress by @lodlev-migdev
* Tray app component by @drunkplato
* draft test build thru PR by @lodlev-migdev
* log pre-deploy inputs by @lodlev-migdev
* Fix faulty import by @gdbroman 
* log pre-deploy inputs by @lodlev-migdev 
* TrayApp positioning fix by @drunkplato 
* remove disabling of workflows to allow for parallel builds by @lodlev-migdev
* more windows updates by @lodlev-migdev 
* Normalized window bounds by @gdbroman
  -  Normalize window bounds in accordance with the [composer agent spec]
  -  Strongly type all  `WindowModel` instances.
  -  Decouple the App and Window models. E.g. a Window can be minimized – an App can't.
  -  Fix the unpinned/pinned apps not exclusive categories issue.
  -  Fix the minimized apps cannot be opened issue.
  -  Add a minimize button to Relic.
* fix #565 by @Tenari 
* Move Storybook to root by @gdbroman

<img width="360" alt="image" src="https://user-images.githubusercontent.com/29574724/218070280-7b6db5ab-5526-480a-9b39-e01d4601b64d.jpg"> 

* Tag based build fix by @lodlev-migdev
* Rm `--rlm-text-color` from global style by @gdbroman

Before | After
--- | ---
![BTN_BEFORE](https://user-images.githubusercontent.com/29574724/218115849-00b513c9-183c-4fc8-84fd-2dd993023288.jpg) | ![BTN_AFTER](https://user-images.githubusercontent.com/29574724/218115884-a1efb33a-bab8-4521-bf46-6c11fd8efde5.jpg)

* Style fixes for row and trays by @drunkplato 
  - the Row component wasn't setting its text color so when we removed the global text style, it always was black. 
  - tray app wouldn't grow when +4 people were in a room
* add enhancement #596 hash details by @Tenari 
* Windows build fixes by @lodlev-migdev 
* 941 contact sharing realm by @leowini 
* Fix docked app status indicator and more by @gdbroman 
  ### Bug fixes:
  -  Fix bug where docked apps' status indicator (for `isOpen`/`isActive`) isn't consistently working
  -  Fix bug where https://github.com/holium/realm/issues/988 by persisting the order in MobX
  -  Fix bug where Relic browser window doesn't rise to top on focus
  ### New stuff:
  -  Add a hide/show context menu option
  -  Opening an app should close the home pane

https://user-images.githubusercontent.com/29574724/218250878-ad6d3328-b799-44a0-86d5-3a79e5bef993.mov

* Load mouse in AppUpdater by @gdbroman
  ## What is changed
  This PR splits out a standalone version of the mouse which listens for mouse events inside its container, as opposed to Electron IPC messages. The standalone mouse is then loaded in the AppUpdater BrowserWindow.

Before | After
--- | ---
<video src="https://user-images.githubusercontent.com/29574724/218331398-27894107-ef25-4b5d-89db-10f4d0f49627.mov" /> | <video src="https://user-images.githubusercontent.com/29574724/218331401-2b289036-932b-4f44-9a90-17ba72707cdd.mov" /> 

* Cleaning up Window & Titlebar components by @gdbroman
  -  Clean up Window and Titlebar component abstractions, types, and file names
  -  Enable bottom-left window resizing
  -  Style windows w/ 90% opacity and blur

https://user-images.githubusercontent.com/29574724/218436345-2e32ea58-045a-459c-9430-83f05b5e5170.mov

* fixed wallet back button on onboarding and removed verb logs from agent by @drunkplato
  * The arrow was falling out of the bottom prior, now is positioned correctly.

<img width="360" alt="image" src="https://user-images.githubusercontent.com/6413077/218435476-1a5c9bf0-c529-4370-80db-567b78f3f3e7.png">

* Switched Add members/friends TextButton to design-system TextButton by @leowini
* release-v0.4.0 by @drunkplato 

### `v0.3.1` - 02/01/23
* rooms relic fix & copy spaces path by @drunkplato
  * minor fixes for rooms and relic browser bug
* copy link context menu option for SpaceRow component
* Save the currently opened space in %spaces by @ajlamarc
  * Add `current` to `%spaces` that stores the currently opened space path
  * Changing spaces in Realm sends a poke to update `current`.  Creating a new space also updates `current`.
  * New subscription path `/current` that sends updates when the space is changed.
* Fix conditional hooks not being caught inside observer components by @gdbroman
* Fix null snapshot on boot by @gdbroman
* release-v0.3.1 by @drunkplato

### `v0.3.0` - 01/30/23
* Remove bitcoin option by @drunkplato
   * more rooms fixes
   * logout now cleans up rooms properly
   * cleaning handshake logic for latency situations
   * fixes a bug where restarting onboarding logs a ship in prior to being done with onboarding.
   * open image attachment in Relic from DMs
   * theme switching bug fix
   * changed workspace build script to link all libs
 * Wallet encryption by @drunkplato
* found a useMemo happening after a return null by @drunkplato
* quick fix by @drunkplato
* Wallet release alpha by @drunkplato
   * Wallet tray app
      * Manage addresses
      * Send / Receive eth, erc-20
      * View NFTs
      * Manage settings
   * Save notes on each transaction 
   * Encryption for credentials and mnemonic
   * Delete HD wallet locally
   * Delete HD wallet metadata on ship
* %realm-wallet agent for storing metadata and sending crypto via @p  
* staging-v0.2.4 by @lodlev-migdev
* Wallet Store -> DiskStore by @drunkplato
* fixed wallet avatar bug and moon truncation in transaction list by @drunkplato
* scrollview fix for webview by @drunkplato
* Fix crash during ship boot by @gdbroman

https://user-images.githubusercontent.com/29574724/215357806-6b5cae54-31f0-4533-93f7-175ac9196721.mov

* Wallet prod rpc fix by @drunkplato
   * useRooms was crashing when click out of the wallet when the Relic browser was open from a transaction link.
   * transaction screen defaults to first address even if on another address.
   * Adding usd conversion to various screens
   * Adding hour and min to transaction details.
   * fix erc-20 coin send transaction 
* Wallet tx to from fix by @leowini
* release-v0.3.0 by @drunkplato

### `v0.2.1` - 01/25/23
* test and fix test-build by @lodlev-migdev
* 489 deployment updates by @lodlev-migdev
  * fixes the useRooms hook to cleanup the context properly.
* 489 deployment updates by @lodlev-migdev
* testing builds by @lodlev-migdev
* staging-v0.1.1 by @lodlev-migdev
* Room connection fixes by @drunkplato
* Rooms dial waiting ack flow fixes 2 by @drunkplato
* Reorder pinned apps by @gdbroman
 * Fix reordering of pinned apps
    * Fix context menu actions (pin & close)
    * Make it so that apps aren't accidentally opened when reordering them
    * Clean up ContextMenu styles + types

https://user-images.githubusercontent.com/29574724/213758027-96815df5-e71b-4f36-a578-8668d8457f75.mov

* Rooms transport udp by @drunkplato
* fix for 'gh release update..' command when running windows build by @lodlev-migdev
* sync'd latest staging and production builds by @lodlev-migdev
* touch to force change so can PR and build by @lodlev-migdev
* added the new urls to the BaseProtocol not useRooms... by @drunkplato
* Update Holium handle in ErrorBoundary by @gdbroman
* Rooms udp fix 2 by @drunkplato
* Fix null space description error by @gdbroman
  *This fixes a bug where the app crashes when you click "Edit" on a space without a description (but only seemed to happen sometimes).
  *Also cleaned up some warnings in `Details.tsx`, like removing use of deprecated `findDomNode`.
  
https://user-images.githubusercontent.com/29574724/214273428-aece2b07-dbe7-4cdd-a9b9-9253f35daceb.mov

* Add PR lint step by @gdbroman
  * Fix all ESLint errors
  * Add a `tsconfig.json` in root for others to extend from
* Rooms udp fix 3 by @drunkplato
* release-v0.1.2 by @lodlev-migdev

### `v0.1.1` - 01/19/23
* release-v0.1.1 by @drunkplato
   * properly refreshes roomsManager context in useRooms
* release-v0.1.1 by @lodlev-migdev
   * fixes the useRooms hook to cleanup the context properly


### `v0.1.0` - 01/19/23 
* release-v.0.1.0 by @lodlev-migdev
* 489 deployment updates by @lodlev-migdev
* * improve the SystemBar design and make Rooms more prominent as a visual element

<img width="452" src="https://user-images.githubusercontent.com/6413077/212691943-23c02ff0-9aa7-4d64-98c1-1afc0a1258f7.png">

* improved build processes
* sys.kelvin update to 16
* updated agent so that leaving a room as a non-creator auto-leaves in the agent
* connection issues fixed
* filtered rooms properly
* fixed popover that didn't appear
* Add reveal input to "Add ship" onboarding step
* Refactor reveal input in hosting settings to use the new `design-system` component
* misc `design-system` cleanups:
   * Make getting css var colors typesafe
   * Make the Icon component use css var colors for filling
* Build out components that will be needed for the browser and other new apps
   * Row
   * Tab
     * Multiplayer
     * Singleplayer
   * Bookmark
   * Folder
   * SectionDivider
   
   Tab
   
   <img width="452" src="https://user-images.githubusercontent.com/6413077/212903328-1fd038f6-8ba5-4769-91ca-8d5b0054b70d.png">
   
   Bookmark
   
   <img width="452" src="https://user-images.githubusercontent.com/6413077/212903395-e6dc9f42-458a-4167-87f0-d29aca60b719.png">
   
   Folder
   
   <img width="452" src="https://user-images.githubusercontent.com/6413077/212903395-e6dc9f42-458a-4167-87f0-d29aca60b719.png">
   
   SectionDivider
   
   <img width="452" src="https://user-images.githubusercontent.com/6413077/212903540-45871932-a0eb-4151-9d33-6fd9647fa8f0.png">
   

### `v0.0.79` - 01/13/23
* 639 right click delete room by @Tenari
* Toolbar rename folder by @ajlamarc
* 640 mute status remote peer by @Tenari
* sub to dm wire in %chat if we aren't already subbed, whenever we send… by @Tenari
* 1-12-23 - nightly fixes by @drunkplato
  * mute status from other peers
  * courier dms now work 
* forcing 0.79 build again by @lodlev-migdev

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
