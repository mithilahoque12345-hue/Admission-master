# Admission Master — Android Studio starter project (v2)

## Included in this prototype
- Subject and chapter selectors for Bangla, English, Higher Math, Biology, ICT, Physics, IQ Solving and Chemistry.
- Admission / HSC practice mode selector and university selector.
- Timed MCQ test, negative marking, score summary, answer review and explanations.
- Local question JSON files and local exam history.

## Important content status
This is a working starter prototype with 16 illustrative practice questions only. It does NOT yet contain 26 years of verified university past-paper questions or a complete HSC textbook question bank. Past-paper questions must be collected and checked against reliable/publicly usable sources; copyrighted textbook material should not be copied wholesale. Original syllabus-aligned questions and explanations can be authored and added.

## Offline and online
The current prototype is offline-first: bundled questions and local history work without internet. It does not yet have a cloud server or online question synchronization. To support both modes, a backend/API and a sync/download mechanism must be added. Once downloaded, question packs can be used offline.

## Build APK
1. Install Android Studio on a computer.
2. Open this folder as an existing project.
3. Sync Gradle and install Android SDK Platform 35 if prompted.
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Find the debug APK at `app/build/outputs/apk/debug/app-debug.apk`.

This project requires Android Studio/Android SDK to compile; this ZIP itself is not an APK.

## Build APK with GitHub Actions
A workflow is included at `.github/workflows/build-apk.yml`. Upload the project contents to a GitHub repository, then open Actions and run `Build Admission Master APK`. Download the `AdmissionMaster-debug-apk` artifact and extract `app-debug.apk`.
