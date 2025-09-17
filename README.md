# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.


---

Tech stack:
- expo
- react native
- nativewind (tailwind css)
- 


Supports:
- ios
- android

packages:
- nativewind
- tailwindcss
- react-native-reanimated
- react-native-safe-area-context

comments:
(setup for styling)
- run "npx tailwindcss init" to generate config file
- copy paste the config data from the reactwind expo docs
- create "globals.css" in app/ route. then import the css data from the reactwind expo docs
- create babel file in root folder and add the data from the reactwind expo docs
- generate metro.config.js using "npx expo customize metro.config.js" and add the data from the reactwind expo docs
- import ./globals.css in the app/_layout.tsx file
- create nativewind-env.d.ts file in the root folder and add the data from the reactwind expo docs
- update this ./app/globals.css in the metro file 

shortcuts:
- rnfes (simple react native code, boilerplate)