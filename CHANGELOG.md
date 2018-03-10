# Taliesin changelog

## 1.1

- Various UI bugfixes and improvements
- Import/Export playlists
- Do not store large cover image in database, instead re-reead it from the file each time it's asked

## 1.0.12

- Add CMake build script

## 1.0.11

- Add docker image and document on how to run Taliesin with Docker
- Set default player name properly 
- Check if stored values still exist on reload

## 1.0.10

- And now we refresh a data source right after creating it

## 1.0.8

- Fix impersonate small bug, improve Manage Data Source

## 1.0.7

- Add minimal install for Raspberry PI
- Allow to build Taliesin without libjwt with the option DISABLE_OAUTH2
- Modify a little bit so a MPD can be added in Carleon via Taliesin interface

## 1.0.6

- Fix memory issue

## 1.0.5

- Bugfixes for Alpine linux

## 1.0.4

- Improve websocket support

## 1.0.2

- Fix front-end when no authentication is set

## 1.0.1

- Fix minor bugs in the backend (lock that wasn't unlocked after use) and front-end (MPD player connector issues)

## 1.0.0

- First release