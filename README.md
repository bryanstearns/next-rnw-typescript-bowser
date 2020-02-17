This is an experiment to create a single project for a React Native mobile app (based on Ignite Bowser) and a Next.js-base web app that uses React Native Web).

I hit a roadblock trying to convert the example Next.js / React-Native-Web app to Typescript - something (babel? webpack? tsc?) doesn't do the same `react-native` -> `react-native-web` module translation that plain Javascript did.

```
cd web
yarn
yarn dev
```
