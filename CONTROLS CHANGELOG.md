# O2 Controls release notes
===========================

1.23 (2019-04-18 16:49:58 +0300)
--------------------------------
- New cast flavour for chromecast support
- Sources reorganization
- Resources reorganization
- Added APIs for separate color tinting for title and time text elements

1.22 (2019-03-29 13:39:05 +0200)
--------------------------------
- SDK should ignore the subtitle format if we can’t parse it

1.21 (2019-03-12 15:13:26 +0200)
--------------------------------
- Updated accessibility ids for buttons and made skip accessibility id dynamic

1.20 (Wed Jan 23 13:30:16 2019 +0200)
-------------------------------------
- Fixed CI build
- Integrated proper designs for skip button
- Implemented skip countdown logic and changed the looks a bit
- Added ad skip button
- Added isSkipButtonVisible field

1.19 (Thu Nov 22 17:04:17 2018 +0200)
-------------------------------------
- Ability to set custom ad controls
- Android min API version downgrade to 16

1.18 (2018-08-31 14:37:18 +0300)
--------------------------------
- Bump minimal Android API to 19

1.17 (2018-08-03 16:12:39 +0300)
--------------------------------
- Moved CC button closer to video duration label
- Chromecast turn off
- Fix zero division crash
- Added Chromecast dependency version check
- Minimal controls flavor (#68)
- Made vpaid ad clickable
- Splitted seekbar and timeLeft visibility properties

1.16 (2018-06-08 17:44:42 +0300)
--------------------------------
- Fixed TV devices not being able to select seek bar when using remote
- Fixed crash when dimensions are less then zero
- Made beon button not clickable when url is not present
- Updated slack token
- Implement BeOn design
- Click url handling
- Overlay advertisement text on branded content video
- Hook up updated gradle plugin for CI/CD with api changes tracking and snapshots
- Public api generation for each flavor
- Rework build script to produce flavour based setup
- Bump gradle version from 4.3 to 4.4

1.15 (2018-04-12 16:02:53 +0300)
--------------------------------
- Fix issue with rescale of controls
- Updated chromecast version
- Fixed Chromecast button not being colored with custom color
- Fix API changes generation bug
- Refactored Chromecast module usage
- Subtitle view removal from controls
- Copyright update
- MIT license

1.14 (2018-03-06 16:31:20 +0200)
--------------------------------
- Close button in TargetUrlActivity
- New close button for clickthrough presenter
- Links handling by WebView
- Click through url embed support for ad controls
- Fixed spinner control not being colored with custom color

1.13 (2018-02-27 13:23:04 +0200)
--------------------------------
- Public API tracking integration
- Chromecast app id should not be accessible
- Talkback strings update
- Midroll markers for android
- Slack integration update
- Travis CD fix
- AssertJ version bump

1.12 (2018-01-18 16:15:21 +0200)
--------------------------------
- AssertJ version bump
