Contacts Content Provider

Aim

To implement data sharing using the Contacts Content Provider in an Android application.

Description

This project demonstrates how to access and display contact information from the device using Android's Contacts Content Provider.

The application uses "ContentResolver" and "ContactsContract" to retrieve contact names and phone numbers.

Technologies Used

- Android Studio
- Java
- XML
- Android SDK
- Contacts Content Provider

Features

- Request READ_CONTACTS permission
- Access device contacts
- Display contact names
- Display contact phone numbers
- Use ContentResolver
- Use ContactsContract

Permission Used

<uses-permission android:name="android.permission.READ_CONTACTS"/>

Main Components

- "MainActivity.java"
- "activity_main.xml"
- "AndroidManifest.xml"

Working

1. The application starts.
2. The user clicks on the Load Contacts button.
3. The application requests contact permission.
4. After permission is granted, the Contacts Content Provider is accessed.
5. Contact names and phone numbers are retrieved.
6. The contacts are displayed in a ListView.

Result

The Contacts Content Provider was successfully implemented, and contact information was retrieved from the device and displayed in the Android application.

Conclusion

This project demonstrates data sharing and accessing contact data using Android's Content Provider framework.
