---
title: Home Climate Controller
permalink: /
---

# Home Climate Controller

Home Climate Controller is a private home automation app for a single household. It runs on a home server and is used only by the people who live in that home. It is not offered to the public and has no other users.

## What the app does

The app automates the home's climate and window coverings:

- **Thermostat schedule.** Sets the home's Google Nest thermostat to the household's chosen temperatures for morning, day, evening, night and away.
- **Room-aware comfort.** Compares temperature sensors in different rooms and adjusts the thermostat so the occupied room reaches the target temperature.
- **Air circulation.** Runs the heating/cooling system's fan for short periods to even out temperatures between rooms.
- **Doors and weather.** Pauses heating or cooling while an exterior door is open, and takes outdoor temperature and sunshine into account.
- **Window shades.** Opens and closes motorized shades based on sun position, weather and time of day.

## Why the app requests Google user data

The app signs in with the household's own Google account and uses the Google Nest **Smart Device Management API** for one purpose: to read the status of the household's own Nest thermostat and sensors (temperature, humidity, heating/cooling mode, set temperature, fan status) and to change the thermostat's set temperature and fan.

It does not request access to email, contacts, files, location history, cameras or any other Google data, and it does not access devices that belong to anyone else.

## Privacy

See the [Privacy Policy](privacy/) for how this data is used, stored and protected.

## Contact

Questions about this app can be raised through the GitHub repository that hosts this page.
