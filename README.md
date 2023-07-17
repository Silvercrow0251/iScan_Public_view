# iScan
<div style="display:flex;">
  <img src="https://user-images.githubusercontent.com/77614961/233616588-9b39a0c9-fff5-46a4-ac09-4e1618f2f8d4.png" width="300" />
  <img src="https://user-images.githubusercontent.com/77614961/233616593-24c5e762-d551-4923-a71b-1d359d1c9885.png" width="300" />
  <img src="https://user-images.githubusercontent.com/77614961/233616597-0a3b3ba2-e331-4b5c-b81f-37250b76469d.png" width="300" />
</div>

[![Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Summary

Introducing iScan, an inventory management app to help keep track of your products in real-time. This app is designed to make tracking inventory simple and efficient. With features like barcode and QR code scanning, users can quickly add items to their inventory by simply scanning the product label. The app also integrates with Google Sheets, making it easy to update inventory data and share it with other team members in real-time.

But that's not all! The app also includes a powerful search function that allows users to quickly find items in their inventory by name, barcode, or QR code. This feature saves time and makes it easier to keep track of inventory levels. Additionally, users can easily add items to their inventory by manually entering product information.

Overall, this scanner mobile app is the perfect tool for businesses looking to streamline their inventory management processes. With features like barcode and QR code scanning, Google Sheets integration, and a powerful search function, users can easily track inventory levels, add new items to their inventory, and quickly find products when they need them. Whether you're running a small business or managing a large warehouse, this app is sure to make inventory management a breeze.

iScan is licensed under Apache License version 2.0.

## Features

- QR and barcode scanning functionality
- Search items by name or barcode
- Google Sheets Integration

## Downloads

<details>
  <summary><strong>v1.0.6 - Enhanced User Data Recording for Non-Google Sign-In Accounts</strong></summary>
  <br/>
  <p><strong>New:</strong></p>
  <ul>
    <li>Fixed an issue where only Google-signed-in users had their usernames recorded due to the ease of verification provided by Firebase for Google accounts. Now, for users who signed up within the app, their email will be recorded for every CRUD operation. This update ensures that Google-signed-in users, who benefit from Firebase's verification process, continue to have their usernames displayed for every CRUD operation. For users who signed up directly within the app using alternative email providers, their email addresses will be recorded instead of usernames, considering the differences in verification processes.</li>
    
  </ul>
  <br/>
  <p><strong>Release Versions:</strong></p>
  <ul>
    <li><strong>iScan v1.0.6</strong></li>
    <li><strong>iScan v1.0.5</strong></li>
    <li><strong>iScan v1.0.4</strong></li>
    <li><strong>iScan v1.0.3</strong></li>
    <li><strong>iScan v1.0.2</strong></li>
    <li><strong>iScan v1.0.1</strong></li>
    <li><strong>iScan v1.0.0</strong></li>
  </ul>
</details>

<details>
  <summary><strong>v1.0.5 - Email, Navigation, and UI Improvements</strong></summary>
  <br/>
  <p><strong>New:</strong></p>
  <ul>
    <li>This update improves the password reset email link by enhancing its appearance and legitimacy. Clear instructions, identifiable branding elements, and trustworthy content and design have been added to improve authenticity. <a href="https://drive.google.com/file/d/15aHGchYDGnMb3aE1r4mRX240-RGYIGXy/view?usp=share_link">Email Reset Link</a></li>
    <li>Improved the app's navigation on the Home Screen. Previously, pressing the back button would lead users to the Splash Screen instead of exiting. The updated version addresses this by displaying a Toast message before exiting, offering users a moment to confirm their action. Moreover, inconsistencies in back navigation across screens have been resolved, resulting in a more seamless experience. These improvements prioritize usability and prevent unintended closures of the app.</li>
    <li>Resolved issues with UI elements not displaying correctly on specific smartphone devices. In the previous version, certain devices experienced problems where UI components were displayed incorrectly, resulting in a suboptimal user experience. To fix this, I identified and addressed the underlying issues related to layout, sizing, alignment, responsiveness, and compatibility with various screen sizes or resolutions. As a result, the updated version of the app ensures that UI elements are now correctly displayed on a wider range of smartphones.</li>
  </ul>
  <br/>
  <p><strong>Release Versions:</strong></p>
  <ul>
    <li><strong>iScan v1.0.5</strong></li>
    <li><strong>iScan v1.0.4</strong></li>
    <li><strong>iScan v1.0.3</strong></li>
    <li><strong>iScan v1.0.2</strong></li>
    <li><strong>iScan v1.0.1</strong></li>
    <li><strong>iScan v1.0.0</strong></li>
  </ul>
</details>

<details>
  <summary><strong>v1.0.4 - Enhanced User Experience and Improved UI</strong></summary>
  <br/>
  <p><strong>New:</strong></p>
  <ul>
  <!-- sound and vibration -->
    <li>The latest update in the inventory application includes a new feature that improves the user experience by providing a vibration feedback whenever an item is scanned. This new feature aims to make the inventory process more engaging and user-friendly, allowing users to easily and quickly identify when an item is successfully scanned.</li>
    <li>In addition to the vibration feedback feature, the latest update of the inventory application also includes some UI improvements.</li>
  </ul>
  <br/>
  <p><strong>Release Versions:</strong></p>
  <ul>
    <li><strong>iScan v1.0.4</strong></li>
    <li><strong>iScan v1.0.3</strong></li>
    <li><strong>iScan v1.0.2</strong></li>
    <li><strong>iScan v1.0.1</strong></li>
    <li><strong>iScan v1.0.0</strong></li>
  </ul>
</details>

<details>
  <summary><strong>v1.0.3 - Bug Fix and Sorting Enhancement</strong></summary>
  <br/>
  <p><strong>New:</strong></p>
  <ul>
    <li>Corrected a bug that didn't log user when deleting an item.</li>
    <li>Enhanced inventory sorting by implementing a new sorting feature that sorts items by date and time instead of stacking new items on top of each other, addressing the previous issue where items were sorted based on incoming items rather than their actual date and time. This update now allows users to sort items based on their updated date and time, while also reflecting the sorting changes in the connected Google Sheets document by automatically moving the updated items to the top of the list.</li>
    <li>With the latest app release, managing your regular and Google Sign In accounts just got easier! You'll now be able to see your Google profile photo in your regular account if you use the same email address for both accounts. This update improves your user experience by providing a more personalized experience. Please keep in mind that this feature is only available to users with a Google Sign In account and matching email address.</li>
  </ul>
  <br/>
  <p><strong>Release Versions:</strong></p>
  <ul>
    <li><strong>iScan v1.0.3</strong></li>
    <li><strong>iScan v1.0.2</strong></li>
    <li><strong>iScan v1.0.1</strong></li>
    <li><strong>iScan v1.0.0</strong></li>
  </ul>
</details>

<details>
  <summary><strong>v1.0.2 - Improved Features and User Experience</strong></summary>
  <br/>
  <p><strong>New:</strong></p>
  <ul>
    <li>In this update, I have addressed the issue of dummy functions appearing when downloading the file. This has been resolved by implementing a filter in the code that removes any dummy functions when downloading the file. As a result, the downloaded file only includes relevant data, which makes it more efficient and user-friendly.</li>
    <li>Improved history log feature that records users and actions. This feature is designed to provide a detailed record of the actions performed by users within the app, which can help with tracking inventory changes and user activity. With the new history log feature, the app will now record and store all user actions, including when an item is added, edited, or deleted from the inventory. In addition to this, the history log will also capture the user who performed the action, along with the date and time the action was taken.</li>
    <li>Implemented a new feature that disables the deletion of the history log. This means that the history log will be continuously tracked and stored, without the possibility of accidental or intentional deletion. This feature is designed to provide more accurate and reliable tracking of inventory changes and user activity. By preventing the deletion of the history log, the app ensures that a complete and detailed record of user actions and inventory changes is maintained.</li>
    <li>In response to user feedback, I have added a new feature to the inventory app that displays the remaining amount when updating an item. With the new feature, when a user updates the quantity of an item, the app will automatically calculate and display the remaining amount. This helps users to ensure that the inventory count is accurate and up-to-date, and reduces the risk of over or understocking of items.</li>
  </ul>
  <br/>
  <p><strong>Release Versions:</strong></p>
  <ul>
    <li><strong>iScan v1.0.2</strong></li>
    <li><strong>iScan v1.0.1</strong></li>
    <li><strong>iScan v1.0.0</strong></li>
  </ul>
</details>

<details>
  <summary><strong>v1.0.1 - New Features and Fixes</strong></summary>
  <br/>
  <p><strong>New:</strong></p>
  <ul>
    <li>This release includes a fix for the sorting issue in the History section of the application whenever an item is added to the inventory. Previously, the sorting would get disrupted and items would not be displayed in chronological order. With this update, the sorting function has been fixed and items are displayed in the correct order based on their date of entry.</li>
    <li>Additionally, this release includes a new feature that allows for the recording of stock in and stock out items in the History section. This will enable users to easily track the stock movement of items and monitor their inventory levels.</li>
  </ul>
  <br/>
  <p><strong>Release Versions:</strong></p>
  <ul>
    <li><strong>iScan v1.0.1</strong></li>
    <li><strong>iScan v1.0.0</strong></li>
  </ul>
</details>

<details>
  <summary><strong>v1.0.0 - Inventory Management App Release </strong></summary>
  <br/>
  <p><strong>New:</strong></p>
  <ul>
    <li>Barcode and QR code scanning functionality for efficient item tracking</li>
    <li>Search function by name or barcode for quick access to items</li>
    <li>Sorted items alphabetically for easier inventory management</li>
    <li>Email/Password and Google sign-in authentication for secure access</li>
    <li>Add, update, and delete items from inventory with ease</li>
  </ul>
  <br/>
  <p><strong>Release Versions:</strong></p>
  <ul>
    <li><strong>iScan v1.0.0</strong></li>
  </ul>
</details>


Source Code (zip):
<strong>[iScan.zip]</strong>

## Code

The majority of the code is written in Kotlin and Java. The code snippet defines several variables, including an AutoCompleteTextView, a TextInputLayout, an EditText, and two constants. These variables are used in an activity or fragment to allow the user to input and filter data. The REQUEST_CODE and text_watcher_tag constants are used for tracking the state of the activity or fragment:

```java
    private AutoCompleteTextView typesFilter;
    private TextInputLayout Category;
    private EditText categoryTextView;
    private static final int REQUEST_CODE = 1;
    private static final String text_watcher_tag = "text_watcher_tag";
```

Initialize Google Authentication Client:

```java
    private static final int RC_SIGN_IN = 120;
    private FirebaseAuth mAuth;
    private GoogleSignInClient googleSignInClient;
```

Setup Realtime Database Security Rules:
```java
{
  "rules": {
    ".read": "auth != null",
    ".write": "auth != null",
    "users": {
      "$uid": {
        ".read": "auth != null && $uid === auth.uid",
        ".write": "auth != null && $uid === auth.uid"
      }
    }
  }
}
```

Make class implement Dropdown List:

```java
        typesFilter = findViewById(R.id.typesFilter);
        Category = findViewById(R.id.Category);

        ArrayAdapter<String> adapter = new ArrayAdapter<>(this, R.layout.dropdown_item, getResources().getStringArray(R.array.categories));
        typesFilter.setAdapter(adapter);
        typesFilter.setOnItemClickListener(new AdapterView.OnItemClickListener() {
            @Override
            public void onItemClick(AdapterView<?> parent, View view, int position, long id) {
                // Do something with the selected item
                String selectedCategory = (String) parent.getItemAtPosition(position);
                // For example, you can set the category as the hint text for the TextInputLayout
                Category.setHint(selectedCategory);

                // Clear the hint text for the TextInputLayout
                Category.setHint("");

                // Set the selected item to the uploadCategory
                uploadCategory.setText(selectedCategory);
            }
        });

        // Set custom dropdown background drawable
        typesFilter.setDropDownBackgroundDrawable(getResources().getDrawable(R.drawable.filter_spinner_dropdown_bg));

        // Set click listener for uploadCategory
        uploadCategory.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                // Open the dropdown menu
                typesFilter.showDropDown();
            }
        });
```

Create a function for Material Date and Time Picker:

```java
        // Set the hint of pickDate to the current date
        SimpleDateFormat dateFormat = new SimpleDateFormat("MMMM dd, yyyy", Locale.getDefault());
        uploadDate.setHint(dateFormat.format(new Date()));

        // Get current time and format to string
        String currentTimeString = DateFormat.getTimeInstance(DateFormat.SHORT).format(new Date());
        // Set hint with formatted current time
        uploadTime.setHint(currentTimeString);

        uploadDate.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                MaterialDatePicker.Builder builder = MaterialDatePicker.Builder.datePicker();
                builder.setTitleText("Select a Date");
                builder.setCalendarConstraints(new CalendarConstraints.Builder()
                        .setValidator(DateValidatorPointForward.now())
                        .build());

                // Set the current date as the initial selection
                Calendar calendar = Calendar.getInstance();
                builder.setSelection(calendar.getTimeInMillis());

                final MaterialDatePicker materialDatePicker = builder.build();
                materialDatePicker.show(getSupportFragmentManager(), "DATE_PICKER");

                materialDatePicker.addOnPositiveButtonClickListener(new MaterialPickerOnPositiveButtonClickListener() {
                    @Override
                    public void onPositiveButtonClick(Object selection) {
                        Date date = new Date((Long) selection);
                        SimpleDateFormat formatter = new SimpleDateFormat("MMMM d, yyyy", Locale.getDefault());
                        String dateString = formatter.format(date);
                        uploadDate.setText(dateString);
                        uploadDate.setBackgroundResource(R.drawable.ok); // set the background back to default
                    }
                });
            }
        });

        uploadTime.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                // Get the current time
                Calendar calendar = Calendar.getInstance();
                int hour = calendar.get(Calendar.HOUR_OF_DAY);
                int minute = calendar.get(Calendar.MINUTE);

                // Create and show the time picker with the current time
                MaterialTimePicker.Builder builder = new MaterialTimePicker.Builder();
                builder.setTimeFormat(TimeFormat.CLOCK_12H);
                builder.setTitleText("Select a Time");
                builder.setHour(hour);
                builder.setMinute(minute);
                final MaterialTimePicker materialTimePicker = builder.build();
                materialTimePicker.show(getSupportFragmentManager(), "TIME_PICKER");


                materialTimePicker.addOnPositiveButtonClickListener(new View.OnClickListener() {
                    @Override
                    public void onClick(View v) {
                        int hour = materialTimePicker.getHour();
                        int minute = materialTimePicker.getMinute();
                        String am_pm = "";

                        if (hour >= 12) {
                            am_pm = "PM";
                            if (hour > 12) {
                                hour -= 12;
                            }
                        } else {
                            am_pm = "AM";
                            if (hour == 0) {
                                hour = 12;
                            }
                        }

                        String time = hour + ":" + String.format("%02d", minute) + " " + am_pm;
                        uploadTime.setText(time);
                        uploadTime.setBackgroundResource(R.drawable.ok); // set the background back to default

                        // Save the selected time as text
                        String selectedTime = String.format("%02d", hour) + ":" + String.format("%02d", minute) + " " + am_pm;
                    }
                });
            }
        });
```

Dropdown List to Create Categories: [Image Preview](https://drive.google.com/file/d/1p_dZRJS8nIsCadCifYVtUlXEas9NIcxP/view?usp=share_link)

```java
    <string-array name="categories">
        <item>Office Supplies</item>
        <item>Arts and Crafts Materials</item>
        <item>Electronic Equipment</item>
        <item>Food Supplies</item>
        <item>Stockpiled Equipment</item>
    </string-array>
```

## Google Sheets Integration: <strong>[Google Sheets]</strong>
<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/77614961/235035646-21cfbc0e-d468-405e-a7b8-2d352d6b8320.png"></td>
    <td><img src="https://user-images.githubusercontent.com/77614961/235035709-a6feb68f-e700-4620-844b-b61d652665b5.png"></td>
  </tr>
</table>

### Instructions to Use

To import data from Firebase into Excel, follow these simple steps:

1. Open a new or existing Excel workbook.
2. Select the cell where you want to import the data from Firebase.
3. Copy the appropriate formula from below, depending on which data you want to import.

- To import Inventory items data:

```java
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
```

- To import History Log data:

```java
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
```

4. Paste the formula into the selected cell in Excel.
5. The first time you use the formula, you will be prompted to sign in to your Google account and grant access to the Google Sheets document containing the formula. Once you have granted access, the data from Firebase will be imported into the selected cell in Excel.

That's it! You can now use this data in Excel as you would with any other data. Note that if you need to import additional data, you can simply copy the formula and paste it into a new cell, updating the URL and sheet name as necessary.

> **Note:**
The "A1:I" in the formula refers to the range of cells that you want to import from the specified Google Sheets document. This range includes all the cells in the first 9 columns of the Inventory sheet of the specified document. If you want to modify the location of the range to include a different set of cells, you can simply change A1:I to the appropriate range. For example, if you want to import all the cells in column A, starting from row 2, you can change the formula to:

```java
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
```

## Backup and Recovery Guide

This guide will walk you through the steps to backup and recover data using Firebase and Google Sheets integration. The backup process is automated and occurs daily, but you can also export and import the JSON file from Firebase to create additional backups as needed. Please note that the provided code creates one emergency backup, which can be managed easily.

### Step-by-Step Guide

1. Open the Google Sheets document that you want to backup.

2. In the first cell where you want to import data, enter the following formula:
```java
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
```
3. This formula imports data from the specified Google Sheets document.

4. Add a new spreadsheet after the first one, enter the following formula:
```java
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
```

5. This formula imports data from the specified Google Sheets document.

6. Your data will now be backed up automatically every day using Firebase and Google Sheets integration.

> **Note:**
This feature automatically creates a backup of your data every day using Firebase and Google Sheets integration. The code is set to backup the data daily for 12 hours, and then updates the next day, which rewrites the old data. However, if you need to make additional backups, you can do so easily.

### Additional Backups
If you need to create additional backups, you can do so easily by exporting or importing the JSON file from Firebase:

1. Open Firebase console and select your project.
2. Go to the "Database" section and select "Export JSON".
3. Save the JSON file to your local machine.
4. To import the JSON file, go to the "Database" section in Firebase console and select "Import JSON".
5. Select the JSON file you want to import and click "Import".
6. Your data will now be backed up in Firebase.

> **Note:**
Follow the steps in this guide to backup and recover your data, and always keep a backup copy in case of emergencies.


## App Demo: [Video](https://drive.google.com/drive/folders/1reh0WVyHA09GwZBeCNzJCkTd5oOxxzME?usp=share_link)
<table>
  <tr>
    <td align="center"><strong>Email and Google Authentication</strong></td>
    <td align="center"><strong>QR and Barcode Functionality</strong></td>
    <td align="center"><strong>Stock In/Stock Out History</strong></td>
  </tr>
  <tr>
    <td align="center">
      <video src="https://user-images.githubusercontent.com/77614961/233758626-3fd54d10-b32d-43c9-a9fd-2493b05783ca.mp4" width="400" height="300" controls></video>
    </td>
    <td align="center">
      <video src="https://user-images.githubusercontent.com/77614961/233632108-a7068b30-ce2c-406f-b08a-f5a5227c7f13.mp4" width="400" height="300" controls></video>
    </td>
    <td align="center">
      <video src="https://user-images.githubusercontent.com/77614961/233878169-5b89e71c-7a84-4796-94c0-24821a54cb06.mp4" width="400" height="300" controls></video>
    </td>
  </tr>
</table>

## Additional Software (Barcode and QR Code Generator)
The Barcode and QR Code Generator is a software application developed using Python and created with the PyCharm coding tool. This software allows users to generate barcode and QR code images and save them into a designated folder. It provides a simple and convenient way to create and store various types of codes for different purposes. <a href="https://drive.google.com/drive/folders/1UcwkmG3CYkeEOHJUOuyubXq3YSdQNG8G?usp=share_link">Project Link</a></li>

### Features

1. Barcode Generation: The software supports the generation of random barcode numbers. The generated barcode will consist of random numbers based on the specified format.
2. QR Code Generation: The software enables the creation of QR codes with alphanumeric combinations.
3. Image Saving: Once the barcode or QR code is generated, the software allows users to save the resulting image into a specified folder on their computer. This feature ensures easy access and organization of the generated codes.
4. User-Friendly Interface: The software offers a simple and intuitive user interface, making it easy for users to generate codes quickly. The interface provides clear instructions and ensures a smooth user experience.

# References
- Firebase Cloud Firestore - https://firebase.google.com/docs/firestore
- Firebase Realtime Database - https://firebase.google.com/docs/database/admin/save-data
- Firebase Cloud Storage - https://firebase.google.com/docs/storage
- Firebase Google Authentication - https://firebase.google.com/docs/auth/android/google-signin
- Code Scanner Library - https://github.com/yuriy-budiyev/code-scanner
- Image Loading Library - https://github.com/bumptech/glide


License
=======
```none
This software is licensed under Apache 2.0, and is available for free use, distribution,
and modification, provided that you comply with the terms and conditions of the license. 
When distributing the software, you must include a copy of the license and any 
copyright notices.

The software is provided "AS IS" with no warranties or conditions of any kind, either 
express or implied, unless required by applicable law or agreed to in writing. Please 
refer to the license text for more information on the specific permissions and 
limitations under the Apache 2.0 License.

You are not obligated to contribute any changes made by others to the original software, 
but any such changes will also be subject to the terms of the license.
