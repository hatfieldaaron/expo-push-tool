# Expo Push Tool (iOS)

A lightweight native SwiftUI app for testing push notifications via the [Expo Push API](https://docs.expo.dev/push-notifications/sending-notifications/).

## 💡 What It Does

- Enter any valid `ExpoPushToken[...]` from an Expo app
- Write a custom notification title and message
- Tap "Send" to deliver it via the Expo Push API
- See the result instantly in-app

## 🚀 Getting Started

1. Build and run the app on an iPhone or simulator
2. Paste a valid Expo Push Token from your own device/app
3. Enter a title and message
4. Tap **Send Notification**

You’ll receive the push notification instantly if the token is active.

## 🔐 Notes

- This app does **not** generate Expo push tokens — it only sends them.
- Expo’s API does **not require authentication**, but token support can be added later.

## 🛠 Built With

- SwiftUI
- URLSession for POST request to Expo API
- Clean and simple UIKit-free interface

## 📄 License

MIT — see the [LICENSE](LICENSE) file for full terms.
