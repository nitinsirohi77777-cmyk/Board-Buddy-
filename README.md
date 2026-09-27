# BoardBuddy MVP

A mobile-first Class 12 board exam companion built with React Native + Expo.

## Fastest mobile method
1. Open Expo Snack in your mobile browser: https://snack.expo.dev/
2. Create a new Snack.
3. Replace the default App.js with the App.js in this folder.
4. Open Expo Go on Android and run the Snack/project.
5. Later move the project to a full Expo project and use EAS Build to create an APK.

This MVP intentionally uses only React Native core components, so there are no extra packages to install.

## Included
- Home dashboard
- Subject/chapter navigation
- Chapter/topic learning screens
- Quick/chapter/subject/mock/mistake test menu
- Working quiz with score
- Revision center
- Study planner
- Progress dashboard
- Profile/settings screen
- Focus timer
- Bottom navigation

## Production architecture
For a real public app, add:
- Firebase Authentication
- Firestore question/content database
- Cloud Functions / secure server for AI calls
- Async local caching
- Push notifications
- Admin dashboard
- Analytics and crash reporting
- Real board syllabus/PYQ content with appropriate rights/licensing
