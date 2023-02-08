# Changelog

## v1.2.0 (2023-01-25)

- Update and fix eslint rules
- Replaced momentjs with native browser api
- Added subtitle settings button
- Added google analytics
- Added transitions for suggestion component and subtitle
- Made suggestions coming from voiceflow appear at the correct time

## v1.1.0 (2022-12-22)

- Fixed visual bugs on iOS
- Added subtitles as customizable tag in the index.html using `<data-subtitles_enabled>`
- Changed logo from Crowdmedia to Unith
- Added green stroke indicating a talking video on defauls screen
- Hide logo on mobile views

## v1.0.11 (2022-11-07)

- Fixed video freeze on some iOS 15 devices
- Fixed double video visual bug on some iOS versions (15 and 16)

## v1.0.10 (2022-10-27)

- Fixed infinite loading screen
- Throw exception if video not playing after firstclick event

## v1.0.9 (2022-10-03)

- Docker builder
- Sentry logs
- mv public into separate repo

## v1.0.8 (2022-08-30)

- Fixed bug where default would be send if user sends 1-3 and there are no suggestions existing
- Fixed linux loadup bug

## v1.0.7 (2022-08-24)

- Undid global API class (introduced in version v1.0.3) as it was causing some issues. Changes made in v1.0.4 to v1.0.6 remain

## v1.0.6 (2022-08-22)

- Fixed a bug in which log in was attempted before deciding which server the app should point to

## v1.0.5 (2022-08-19)

- Made possible to use the full UI. Check README.md on instructions

## v1.0.4 (2022-08-19)

- Made css class names consistent on each build.

  **NOTE**: Even though now you can override the default styling in any way you please, we give no guarantee that we won't change the styles or class names without notice in the future.

## v1.0.3 (2022-08-19)

- Improved the way we communicate to our servers (global API class)
- Made it easier to change which server we use when we deploy

## v1.0.2 (2022-08-05)

- Made possible to reconnect to our servers if connection drops, while mantaining the conversation state
- Fixed a styling bug on the chat component
- added error screen if a video does not exist
- Added head name as the browser tab description

## v1.0.1 (2022-07-27)

- Touch to start icon is now customizable using the `<data-touch_to_start_icon>` tag in the index.html.
- Always use three dots loading animation when user is waiting for server response, deleted waiting-text in default screen.
- Add deprecation warning error message. In case there will be a breaking change, you will be notified if using an unsuported frontend version.
- Bugfixes

## v1.0.0 (2022-06-27)

### initial release

Initial release of the app
