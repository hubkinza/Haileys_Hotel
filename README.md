# Haileys Hotel

## Purpose of the Project
Haileys Hotel is a fictional hotel website designed to showcase an elegant, user-friendly interface for potential customers. The project demonstrates the ability to create a fully responsive, accessible, and visually appealing multi-page website using only HTML and CSS. It aims to provide users with an easy way to explore rooms, book their stay, and contact the hotel.

## Value for Users
- Easy navigation across essential hotel services.
- Clear and responsive layout that works on all devices.
- A professional and clean design that enhances user trust and engagement.


## Project Structure
- All files are clearly named, consistently lowercase, and grouped logically (e.g., `assets/` folder for images).
- The CSS is separated into an external `style.css` file, linked in the HTML `<head>`.
- Code is organized and commented for easy readability and maintainability.

## Screenshots
Here are some screenshots of the final implementation:

| Homepage (`index.html`) | Booking Page (`booking.html`) |
|:---|:---|
| ![Homepage Screenshot](assets/screenshots/homepage.png) | ![Booking Page Screenshot](assets/screenshots/booking.png) |

| View Rooms (`viewrooms.html`) | Contact Us (`contactus.html`) |
|:---|:---|
| ![View Rooms Screenshot](assets/screenshots/viewrooms.png) | ![Contact Us Screenshot](assets/screenshots/contactus.png) |

> **Note:** Upload your screenshots into the `assets/screenshots/` folder and make sure the file paths match.

These screenshots align with the user stories, such as **viewing rooms**, **booking a stay**, and **contacting the hotel**.

## Testing Process
### Css Validator 
Index.html


Viewroom.html

Booking.html

Contactus.html


### HTML validator

### Functionality Testing
- ✅ Navigate through all pages using menu links to ensure correct linking.
- ✅ Fill out the booking form and the contact form to confirm field accessibility and basic validation.
- ✅ Test the responsiveness by manually resizing the browser window and checking different device views (mobile, tablet, desktop).

### Usability Testing
- ✅ Verify that important pages and links are easily discoverable.
- ✅ Check that the form fields are labeled and easy to understand.
- ✅ Confirm that the color scheme, typography, and layout contribute to a pleasant user experience.

### Responsiveness Testing
- ✅ Test using Chrome DevTools (mobile view) for different screen sizes like iPhone SE, iPad, and desktop.
- ✅ Check on an actual mobile device to ensure real-world responsiveness.

### Broken Links Testing
- ✅ Click every navigation link manually to confirm there are no 404 or broken pages.
- ✅ Use an online broken link checker tool to scan the site and ensure all links are valid.

## Manual Testing

| **Test Scenario**                          | **Action**                                 | **Expected Result**                              | **Actual Result** | **Pass/Fail** |
|:--------------------------------------------|:-------------------------------------------|:-------------------------------------------------|:-----------------:|:-------------:|
| Navigation Links                            | Click on all navbar links                  | Navigate to the correct page without errors      | Works as expected | Pass |
| Booking Form Submission                     | Fill and submit booking form               | Form fields should accept input correctly        | Works as expected | Pass |
| Contact Form Submission                     | Fill and submit contact form               | Form fields should accept input correctly        | Works as expected | Pass |
| Broken Links Check                          | Check all links manually and using tool    | No broken links, all links active                | Works as expected | Pass |
| Mobile Responsiveness (iPhone SE size)       | Resize screen or use DevTools              | Layout adjusts correctly for mobile screens      | Works as expected | Pass |
| Tablet Responsiveness (iPad size)            | Resize screen or use DevTools              | Layout adjusts correctly for tablets             | Works as expected | Pass |
| Desktop Responsiveness (Full Screen)         | Open on large desktop screen               | Layout stays centered and professional looking   | Works as expected | Pass |
| Readability and Accessibility (color/contrast) | Review site visually                      | Text is easily readable with good contrast       | Works as expected | Pass |
| Image Display                               | Check images on all pages                  | Images load properly without distortion          | Works as expected | Pass |
| Form Labels and Inputs                      | Review form accessibility                 | Labels are clearly linked to their input fields   | Works as expected | Pass |

## Deployment

The project was deployed using **GitHub Pages** by following these steps:
1. Go to the GitHub repository.
2. Click on **Settings** > **Pages**.
3. Under **Branch**, select `main` and the `/root` folder.
4. Click **Save**.
5. After a few minutes, the live site is available at:  
   [Haileys Hotel Live Site](https://hubkinza.github.io/Haileys_Hotel/)
