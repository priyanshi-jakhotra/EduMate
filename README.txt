================================================================================
                        EDUMATE - OFFLINE AI ACADEMIC HELPER
                              README / PROJECT GUIDE
================================================================================

ABOUT THIS PROJECT
------------------
EduMate is an Android application designed to help students with their studies.
It works completely OFFLINE without needing internet connection.
All data is stored locally using SQLite database.

Language: Java
UI: XML Layouts
Database: SQLite
Min Android Version: 7.0 (API 24)


CURRENT FEATURES (50% Complete)
-------------------------------
1. Login - User authentication with database
2. Registration - Create new user account
3. Dashboard - Main navigation screen
4. Ask AI - Get answers using keyword matching


HOW TO RUN THIS PROJECT
-----------------------
Step 1: Open Android Studio
Step 2: Click on "Open" and select the EduMate folder
Step 3: Wait for Gradle sync to complete (may take few minutes)
Step 4: Connect your Android phone OR start an emulator
Step 5: Click the green "Run" button (or press Shift + F10)
Step 6: Select your device and click OK
Step 7: App will install and open on your device


HOW TO USE THE APP
------------------
1. REGISTRATION
   - Open the app
   - Click "New User? Register"
   - Fill all fields (Name, Email, Phone, Username, Password)
   - Click Register button

2. LOGIN
   - Enter your username and password
   - Click Login button

3. DASHBOARD
   - Shows welcome message with your name
   - Click "Ask AI" button to use AI feature

4. ASK AI
   - Type any question in the text box
   - Click "Get Answer" button
   - Try asking: algebra, calculus, physics, newton laws, data structures


PROJECT FILES
-------------
Java Files:
- LoginActivity.java        (Login screen)
- RegisterActivity.java     (Registration screen)
- DashboardActivity.java    (Main menu)
- AskAIActivity.java        (AI question answering)
- DatabaseHelper.java       (Database operations)

XML Layouts:
- activity_login.xml
- activity_register.xml
- activity_dashboard.xml
- activity_ask_ai.xml


DATABASE TABLES
---------------
1. users - Login information
2. subjects - Subject list
3. topics - Topics with notes
4. questions - Quiz questions
5. syllabus - Course content
6. qa_pairs - AI question-answers


REQUIREMENTS
------------
- Android Studio (Latest version)
- JDK 11 or higher
- Android SDK 34


HOW TO BUILD APK
----------------
1. Open Android Studio
2. Go to Build menu
3. Click "Build Bundle(s) / APK(s)"
4. Select "Build APK(s)"
5. Wait for build to complete
6. APK will be in: app/build/outputs/apk/debug/


TROUBLESHOOTING
---------------
Problem: Gradle sync failed
Solution: Check internet and click "Try Again"

Problem: App not installing
Solution: Enable USB debugging on phone


================================================================================
                              END OF README
================================================================================
