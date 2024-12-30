# Wargames.MY CTF 2024 World 2

## Description

Welp, time to do it again.

Unable to install? That is a part of the challenge, try to overcome it.

## Files attached

- `World_II.apk`

## Solve procedure

### Extracting the data from the APK

We are going to extract the data from the APK and manually disect it.

Inside the APK's `assets/www` folder we can see a familiar file structure that resembles the one from World 1.

![](image-5.png)

To run the game we just swapped the data from the APK into the extracted World 1 executable data, changed the health of the bosses and then we saw that the QR code was this time stored as `QR Code 5A`

## Flag

Later