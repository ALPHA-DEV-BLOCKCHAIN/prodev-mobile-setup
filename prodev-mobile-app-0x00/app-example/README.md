# Create Your First Mobile App

This project was created as part of the ALX Mobile App Development module. The goal was to set up a simple Expo-based React Native app, verify that it runs correctly, and document the reset process using the `reset-project` script.

---

## Project Setup and Scaffolding Steps

1. **Initialized the Project**
   - Created a new Expo app using the provided template:
     ```bash
     npx create-expo-app app-example
     ```
   - Navigated into the project directory:
     ```bash
     cd app-example
     ```

2. **Started the Development Server**
   - Ran the app locally with:
     ```bash
     npx expo start
     ```
   - For iOS devices, scanned the QR code in the terminal using the phone’s Camera app.  
     For Android devices, scanned the QR code using the Expo Go app.

3. **Edited the Home Screen**
   - Opened the file `app/index.tsx` and updated the text displayed on the screen from the default to:
     ```
     First App Created
     ```

---

## Resetting the Project

To reset the project and observe its behavior, I ran:
```bash
npm run reset-project
