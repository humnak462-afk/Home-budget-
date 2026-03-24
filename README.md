# Firebase Safety App 

This repository contains a cleaned Android (Java) project based on your provided pages and steps.

## What is included

- Project-level build.gradle with classpath 'com.google.gms:google-services:4.2.0'.
- Module-level app/build.gradle aligned to SDK 26 and your requested dependencies.
- Firebase login and register flows (Login, Register).
- Emergency text sync page (Emergency) with realtime database keys ab and abc.
- Women safety page (Women) with location upload and emergency flag.
- Google Maps tracking screen (MapsActivity).
- Navigation drawer host (Main2Activity) and splash screen (MainActivity).
- AndroidManifest entries and required permissions.

## Required manual step

Add your Firebase config file:

- Download google-services.json from Firebase console.
- Place it at: app/google-services.json

## Build notes

This project intentionally keeps the old Android support libraries and Firebase versions that you requested so it matches the original material.