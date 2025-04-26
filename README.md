# Haileys Hotel

## Purpose of the Project
Haileys Hotel is a fictional hotel website designed to showcase an elegant, user-friendly interface for potential customers. The project demonstrates the ability to create a fully responsive, accessible, and visually appealing multi-page website using only HTML and CSS. It aims to provide users with an easy way to explore rooms, book their stay, and contact the hotel.You can view the deoplyed site [here](https://hubkinza.github.io/Haileys_Hotel/)

## Value for Users
- Easy navigation across essential hotel services.
- Clear and responsive layout that works on all devices.
- A professional and clean design that enhances user trust and engagement.


## Project Structure
- All files are clearly named, consistently lowercase, and grouped logically (e.g., `assets/` folder for images).
- The CSS is separated into an external `style.css` file, linked in the HTML `<head>`.
- Code is organized and commented for easy readability and maintainability.
  ## UI Colors
  ![color](https://github.com/user-attachments/assets/2d74e493-fd8e-45d0-8e5a-b469ad887e4f)


The color scheme for Haileys Hotel was carefully chosen to create an elegant, calm, and refined atmosphere, ideal for a hospitality brand.

| **Colour Name** | **Hex Code** | **Role in Design** | **Color Theory** |
|:----------------|:-------------|:-------------------|:-----------------|
| Rosewood Blush  | `#A75878`     | Primary / Accent Colour | Rosewood Blush and Orchid Bloom are analogous hues (next to each other on the color wheel) in the red-violet to violet range. This creates a harmonious and soothing effect, ideal for hospitality brands like a hotel that want to appear elegant, calm, and refined. |
| Orchid Bloom    | `#A7589F`     | Secondary Accent   | Same analogous relationship as Rosewood Blush, enhancing a sense of unity and sophistication. |
| Lavender Mist   | `#DBD3DC`     | Background / Neutral Tone | A soft lavender-grey balances the vibrant tones by offering a gentle, clean background, making the bold colors pop without overwhelming the eye. Great for UI/UX design where readability and aesthetic balance are essential. |
| Deep Plum       | `#300833`     | Text / Contrast / Callouts | Deep plum complements the lighter tones and conveys luxury, mystery, and depth, providing strong contrast for headings, callouts, and important elements. |

## User stories 
### Hotel Website Features

### Feature: Hotel Landing Page

As a user  
I want to view a beautiful landing page  
So that I can get a welcoming first impression of Hailey’s Hotel

#### Scenario: Viewing the homepage
Given I visit the hotel’s website  
Then I should see the name "Hailey's Hotel"  
And I should see an introduction about the hotel  
And I should see a call-to-action button to "View Rooms"

---

### Feature: Navigation Bar

As a user  
I want to navigate easily across pages  
So that I can find information quickly

#### Scenario: Viewing the navigation menu
Given I am on any page of the website  
Then I should see navigation links to "Home", "View Rooms", "Booking", and "Contact Us"

---

### Feature: View Rooms

As a user  
I want to browse available rooms  
So that I can decide which room I’d like to book

#### Scenario: Viewing room cards
Given I click on "View Rooms"  
Then I should see a list of room options  
And each card should show a room image, name, and a "Book Room" button

---

### Feature: Booking Page

As a user  
I want to fill out a booking form  
So that I can reserve a room for specific dates

#### Scenario: Filling out the booking form
Given I click on "Book Room"  
Then I should be taken to a booking form  
And I should be able to enter check-in and check-out dates  
And enter my name, phone number, and email  
And click a “book” to complete the booking

---

### Feature: Contact Page

As a user  
I want to access contact details for the hotel  
So that I can reach out for questions or special requests

#### Scenario: Viewing the contact page
Given I click on "Contact Us"  
Then I should see a contact form or contact information

## Screenshots
Here are some screenshots of the final implementation:
### Landing page 
![screencapture-hubkinza-github-io-Haileys-Hotel-2025-04-26-22_18_21](https://github.com/user-attachments/assets/398508d8-a23b-4028-9e4f-bf91a5ada623)

### View rooms Page
![screencapture-hubkinza-github-io-Haileys-Hotel-viewrooms-html-2025-04-26-22_18_38](https://github.com/user-attachments/assets/dec28be4-3911-4c9a-ad8c-87894cb452ae)

### Booking Page
![screencapture-hubkinza-github-io-Haileys-Hotel-booking-html-2025-04-26-22_18_53](https://github.com/user-attachments/assets/851af155-3485-4e2b-9cdf-11ede539a959)


### Contact US page
![screencapture-hubkinza-github-io-Haileys-Hotel-contactus-html-2025-04-26-22_19_23](https://github.com/user-attachments/assets/293ee847-73e0-4f92-8f81-3351c00c9c01)


These screenshots align with the user stories, such as **viewing rooms**, **booking a room**, and **contacting the hotel**.

## Testing Process
### Css Validator 
![css](https://github.com/user-attachments/assets/c986e007-ae7c-49f3-a0d7-bf552a460d01)

### HTML validator
Index.html
![index](https://github.com/user-attachments/assets/9ecaa643-98db-4259-96af-ff42be5d8024)


Viewroom.html
![viewrooms](https://github.com/user-attachments/assets/221c0415-a630-4d2f-a3c8-1794a74e4977)

Booking.html
![booking](https://github.com/user-attachments/assets/446043cc-0580-4102-9ce0-78595fabdc43)

Contactus.html
![contact us](https://github.com/user-attachments/assets/c5911ca9-c753-484b-b718-eebbb797998d)




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

## Future Improvements

The following features and enhancements are planned for future updates to Haileys Hotel:

| **Improvement Area**         | **Planned Enhancement** |
|:------------------------------|:------------------------|
| Add Dedicated Pages           | Create full pages for the "Things To Do" and "Dining" sections currently linked on the landing page. |
| Enhance Forms                 | Implement form validation using JavaScript for better user experience and data accuracy. |
| Accessibility Improvements    | Improve ARIA labels, keyboard navigation, and screen reader support to enhance accessibility for all users. |
| Advanced Styling              | Add subtle animations (hover effects, scroll animations) using CSS or lightweight libraries for a dynamic and modern look. |
| Booking System Integration    | Connect to a real booking engine or backend system to allow users to make live room reservations. |


## Deployment

The project was deployed using **GitHub Pages** by following these steps:
1. Go to the GitHub repository.
2. Click on **Settings** > **Pages**.
3. Under **Branch**, select `main` and the `/root` folder.
4. Click **Save**.
5. After a few minutes, the live site is available at:  
   [Haileys Hotel Live Site](https://hubkinza.github.io/Haileys_Hotel/)
