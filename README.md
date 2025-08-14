# Dream Job Visiting Card App

## Project Overview

This is a simple Android application designed to generate a "Dream Job" visiting card. It provides a beautiful and clean UI that is fully customizable. The app is built with modern Android development practices, using `ConstraintLayout` for a flexible design and CardView for a polished look.

The primary goal of this project is to provide a template for students and developers to create and customize their own digital visiting cards easily.

## Features

- **Beautiful UI:** A visually appealing visiting card layout with a clean design.
- **Responsive Design:** The layout is built to adjust to different screen sizes and orientations.
- **Easy Customization:** All the information on the card (company name, employee details, contact info) is stored in a resource file, making it simple to change.
- **Non-Rotating UI:** The app is configured to remain in portrait mode, providing a consistent user experience.

## How to Customize

This project is designed to be easily customized to fit your personal details. All the user-editable information is located in the `strings.xml` file.

1.  **Open the Project:** Open the project in Android Studio.
2.  **Navigate to `strings.xml`:** Go to `app` -> `res` -> `values` -> `strings.xml`.
3.  **Edit Your Details:** You can change the following values to your own:
    - `company_name`: The name of your dream company.
    - `employee_name`: Your name.
    - `job_title`: Your dream job title.
    - `phone_number`: Your phone number.
    - `address`: Your address.
    - `email`: Your email address.
4.  **Change the Logo:** To change the company logo, replace the image file in the `res/drawable` folder. The current logo file is named `companylogo.png`. Make sure your new image file is also named `companylogo.png` or update the `android:src` attribute in `activity_main.xml` to point to the new file name.
5.  **Change Colors and Dimensions:** You can also modify the colors and dimensions of the UI elements by editing `colors.xml` and `dimens.xml` in the same `res/values` folder.

## Technologies Used

* **Language:** Kotlin
* **Layout:** XML
* **Android Components:** `ConstraintLayout`, `CardView`, `LinearLayout`, `TextView`, `ImageView`

A README file is one of the most important parts of a GitHub project. You can find more information about [creating a README file for your project](https://www.youtube.com/watch?v=7Tk15l23Ctg) by watching a video.
http://googleusercontent.com/youtube_content/0
