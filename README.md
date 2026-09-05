# Attendance & OT Management App

Features:
- Madurai, Hostel, Rameshwaram, Uzhavar Santhai
- Morning/Afternoon/Night shifts
- Employee management
- Present/Absent
- OT hours
- Camera photo
- SQLite database
- Records
- Monthly report

Setup:
1. flutter create attendance_ot_app
2. Copy this package's pubspec.yaml and lib folder into the Flutter project.
3. Add CAMERA permission to android/app/src/main/AndroidManifest.xml:
   <uses-permission android:name="android.permission.CAMERA" />
4. flutter pub get
5. flutter run
6. flutter build apk --release
