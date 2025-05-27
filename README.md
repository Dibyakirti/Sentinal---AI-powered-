# Sentinal---AI-powered-
Sentinel: AI-Powered is a mobile app that identifies plants and animals offline using AI. Built with Java and TensorFlow Lite, it ensures privacy, works without internet, and aids students, trekkers, and farmers. It promotes biodiversity awareness and offers fast, accurate results in real-time. Sentinel: AI-Powered Offline Flower Identifier Sentinel is a novel mobile application designed to identify flowers using machine learning — entirely offline. Built with privacy and accessibility in mind, it helps travelers, nature lovers, and researchers recognize plant species without relying on the internet.

Features Offline Flower Detection: Works even in forests, trails, or remote regions. High Accuracy: Tested to classify species like Rose and Daisy with over 90% precision. Privacy-Safe: No data leaves the user’s phone — ever. User-Friendly Interface: Simple image capture and prediction flow.

Tech Stack Language: Java ML Framework: TensorFlow Lite (.tflite model) Android SDK: CameraX, ML Kit IDE: Android Studio Hardware: Android smartphones

Installation

Open in Android Studio
Connect an Android device or use an emulator
Run the project
Problem Statement Identifying flora in remote areas is challenging due to lack of connectivity and expert resources. Cloud-based apps raise privacy concerns by uploading sensitive data like images and location.

Implementation Steps

Android App Development: Created in Android Studio with a native Java base.
Model Integration: Lightweight TFLite model integrated for local inference.
Performance Testing: Ensured speed and accuracy across devices.
Inference Timing: Used SystemClock.uptimeMillis() to measure processing time.
Results

90% classification accuracy across tested flower types. Zero dependency on internet or cloud servers. Seamless user experience in disconnected environments.

Future Scope- Expand flower database for wider classification. Integrate AR-based plant visualization. Add multi-language support for wider accessibility.
