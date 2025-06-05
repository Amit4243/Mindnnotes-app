## Technologies Used
- React Native (with Expo SDK)
- expo-router
- TypeScript
- Tailwind CSS via Nativewind

## Design Rationale
The app is designed to help users journal their thoughts quickly and track moods. The UI is kept clean and minimal to reduce friction.

## How to Run Locally
1. Clone the repo
2. Run `npm install`
3. Start app: `npx expo start`

## Usability Heuristics
- Feedback: Toast after saving entry
- Discoverability: Clear tabs and labels
- Error prevention: Required fields validation


# Mindnnotes-app
I've generated a basic journaling app called MindNotes using React Native with Expo and expo-router. It includes:

Two screens: Home (for writing entries) and Entries (for viewing).

Bottom tab navigation

Mood selection with emoji

Usability features like validation and feedback alerts

Tailwind CSS support with nativewind
● Technologies used

React Native: For building the cross-platform mobile application.

Expo Router: To manage navigation between screens (Home and Entries).

React Native Safe Area Context: For handling layout within safe areas.

JavaScript/TypeScript: For logic and component development.



---

● Brief design rationale

The app is designed to be simple, intuitive, and fast for users to log their daily moods and journal entries. The focus is on minimal interaction — selecting a mood and writing a short entry — which lowers the barrier to consistent usage. The emoji-based mood selection offers a quick, expressive interface.


---

● How to run the app locally

1. Make sure you have Node.js and Expo CLI installed.


2. Clone the repository and navigate to the project directory.


3. Run npm install or yarn to install dependencies.


4. Start the app with npx expo start.


5. Use the Expo Go app on your mobile device or an emulator to preview the app.




---

● Which usability heuristics you focused on and how

Error Prevention: Alerts users when trying to save an empty journal entry.

Visibility of System Status: Confirmation alerts ("Entry saved!") reassure users their action was successful.

User Control and Freedom: Users can freely select moods and edit entries before saving.

Consistency and Standards: Uses common mobile design patterns like bottom tab navigation and familiar emoji icons.
