# Bajaj Finance Personal Loan – Callback Manager (Native Android)

Native Android app source for customer callback reminders.

## Features
- Customer name, phone number, loan limit, reason
- Exact callback date/time picker
- Android `AlarmManager.setExactAndAllowWhileIdle()` reminder
- High-priority notification with Call action
- Call customer directly from the list
- Mark Done / Undo / Delete
- Data stored locally on the device
- Reschedules reminders after reboot/timezone changes
- Android 13+ notification permission
- Android 12+ exact-alarm permission flow
- Red Bajaj-style professional UI

## Build in Android Studio
1. Open this folder in Android Studio.
2. Let Gradle sync and install the Android SDK requested by the project (compileSdk 35).
3. Connect the Samsung A14 with USB debugging enabled, or create an emulator.
4. Press Run.
5. On first launch, tap **Allow Notifications** and allow exact alarms when Android opens Settings.

## Important for Samsung/Android
For the most reliable exact-time callbacks, allow notifications and exact alarms. If Samsung places the app under battery sleeping/background restrictions, remove the restriction for this app. Exact alarm delivery is still subject to Android/OEM power-management behavior.

## Package
`com.ganesh.bajajcallback`
