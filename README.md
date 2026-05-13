NAMMA METRO SAHAYA - SETUP GUIDE and readme File

Developer: Mohammed Ayan

--------------------------------------------------

REQUIREMENTS

1. Android Studio
2. Firebase Account
3. Internet Connection

--------------------------------------------------

STEP 1 - OPEN THE PROJECT

1. Open Android Studio
2. Click Open
3. Select the NammaMetroSahaya project folder
4. Wait for Gradle Sync to complete

--------------------------------------------------

STEP 2 - CREATE FIREBASE PROJECT

1. Open:
   https://console.firebase.google.com/

2. Click:
   Create Project

3. Enter any project name

4. Finish creating the project

--------------------------------------------------

STEP 3 - CONNECT ANDROID APP TO FIREBASE

1. Inside Firebase click:
   Add App → Android

2. Enter this package name exactly:

   com.nammametro.sahaya

3. Click Register App

--------------------------------------------------

STEP 4 - DOWNLOAD GOOGLE-SERVICES.JSON

1. Firebase will generate:
   
   google-services.json

2. Download the file

3. Paste the file inside:

   NammaMetroSahaya/app/

IMPORTANT:
The file must be placed directly inside the app folder.

--------------------------------------------------

STEP 5 - ENABLE FIREBASE AUTHENTICATION

1. In Firebase Console open:
   
   Authentication

2. Click:
   
   Get Started

3. Open:
   
   Sign-in Method

4. Enable:
   
   Email/Password

--------------------------------------------------

STEP 6 - CREATE NVIDIA API KEY

1. Open:
   
   https://build.nvidia.com/

2. Create account / Login

3. Search this model:

   mistralai/mistral-large-2-instruct

4. Open the model

5. Click:
   
   View Code

6. Click:
   
   Generate API Key

7. Copy the generated API key

--------------------------------------------------

STEP 7 - ADD API KEY IN PROJECT

1. Open project in Android Studio

2. Press:

   Ctrl + Shift + F

3. Search:

   ADD_YOUR_API_KEY

4. Replace all ADD_YOUR_API_KEY values
   with your actual NVIDIA API key

API key locations:

1. AIAssistantActivity.kt
2. ExitFinderActivity.kt
3. VisualGuideActivity.kt

5. Save all files

--------------------------------------------------

STEP 8 - SYNC PROJECT

1. Click:
   
   Sync Now

2. Wait for Gradle build to complete

--------------------------------------------------

STEP 9 - RUN THE APP

1. Connect Android phone
   OR
   Start Emulator

2. Click Run ▶

3. App should start successfully

--------------------------------------------------

IMPORTANT NOTES

1. Do NOT share your API key publicly

2. Do NOT upload google-services.json
   to public GitHub repositories

3. Internet connection is required

4. Firebase Authentication must be enabled

--------------------------------------------------

PROJECT SHARED FOR INTERNSHIP PURPOSE ONLY
