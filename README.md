# Barefeet Dance Company & School Website

## 1. Project Overview

**Barefeet Dance Company & School** is a dedicated, single-page website created for a Brazilian-Middle Eastern Belly Dance company operating in Dublin, Ireland. The project’s central goal is to effectively serve two distinct user demographics: 
**prospective students** looking to enroll in dance classes and 
**clients/event planners** seeking to book professional performances.

The site aims to simplify the process of engagement for both groups by providing clear navigation, detailed schedules, and specific contact forms. It is designed to be highly accessible and responsive, showcasing the passion, diversity, and professional quality of the company's artistic offerings to encourage immediate sign-ups and quote requests.

<img width="1230" height="803" alt="Screenshot 2025-10-27 140356" src="https://github.com/user-attachments/assets/1ddc8afe-f938-4593-ad35-4172d53637e1" />


---

## 2. Features

This project is built around providing clear paths for both students and clients.

### Existing Features

- **Navigation Bar**
  - The responsive navigation bar is **fixed to the top** and appears on all pages (`index.html`,`gallery.html`, `booking.html`, `quote.html`), providing consistent links to Home, Classes, Events, About Us, Gallery, and Contact.
  - **Value to the User:** It ensures effortless navigation across the entire site regardless of device size and includes **dual primary CTAs** ("Book Your Trial Class" and "Get a Performance Quote") in the header to direct users to the two main conversion goals.
   <img width="1900" height="98" alt="Screenshot 2025-10-27 135946" src="https://github.com/user-attachments/assets/caf3e48c-c128-4ffa-8903-ed29b1794116" />
  
- **The Landing Page**
  - Features an impactful image with a clear, concise mission statement and a prominent primary call-to-action (CTA): **"Book Your Trial Class."**
  - **Value to the User:** The immediate visual appeal and clear CTA introduce the company's professional standard and provide the quickest route for new students to start their journey.
    <img width="577" height="606" alt="Screenshot 2025-10-27 140723" src="https://github.com/user-attachments/assets/dc27f19b-48cf-47b7-902d-1c771887ee18" />
  
- **About Us Section**
  - Introduces the company's unique ethos: "Where Latino America meets Middle East," highlighting the Brazilian heritage and passion.
  - **Value to the User:** Uses a **Bootstrap Collapse component** (the "Learn More" button) to hide extended text, allowing users to choose to read the detailed company history and mission without overwhelming the initial view.
    <img width="564" height="625" alt="Screenshot 2025-10-27 140821" src="https://github.com/user-attachments/assets/c6e02ff6-d9ab-4882-be3c-c08b166b6443" />

- **Events Section with Carousel**
  - Displays upcoming performance dates and titles (e.g., "Ballad Moon," "Im.Migration") using a **Bootstrap Carousel** for visual engagement.
  - **Value to the User:** Keeps potential clients and fans updated on public performance dates and includes a clear, secondary CTA: **"Get Your Quote"** to encourage private performance bookings.
    
    <img width="389" height="729" alt="Screenshot 2025-10-27 140853" src="https://github.com/user-attachments/assets/7f76b14d-ff9e-4851-83a8-91393aed175f" />
    <img width="379" height="372" alt="Screenshot 2025-10-27 140900" src="https://github.com/user-attachments/assets/166e82bd-72e0-42c4-83d6-629eeaa8718e" />


- **Classes Section with Schedule Table**
  - Provides a clear schedule using a **responsive HTML Table** (`table-dark`, `table-hover`) detailing class level (Beginner, Intermediate), day, time, and instructor.
  - **Value to the User:** The user can instantly check availability and find a class that fits their schedule and skill level, addressing their primary need upon visiting the school section.
    <img width="1204" height="745" alt="Screenshot 2025-10-27 140928" src="https://github.com/user-attachments/assets/02b91c19-d8f8-4fd0-abd9-bcffa06db94d" />

 
- **Dedicated Booking Forms (Not shown in `index.html` but linked)**
  - The project includes separate pages for **Trial Class Booking** (`booking.html`) and **Performance Quotes** (`quote.html`).
  - **Value to the User:** Forms are highly specific, ensuring students don't have to fill out event logistics and vice versa. This streamlined approach improves the user experience and data quality.
  <img width="388" height="622" alt="Screenshot 2025-10-27 141054" src="https://github.com/user-attachments/assets/0c2a79b9-8da6-47bb-8619-d37dc34ce4ab" />
  <img width="391" height="703" alt="Screenshot 2025-10-27 141107" src="https://github.com/user-attachments/assets/97c0b015-fc99-4583-b7b0-3c0e51d2fd96" />
  <img width="389" height="742" alt="Screenshot 2025-10-27 141122" src="https://github.com/user-attachments/assets/c90bf3f7-908f-40c1-8997-6b5a136eb77f" />


- **Gallery Page (gallery.html)**
  - This dedicated page showcases the company's artistic range through visual media, featuring professional photographs of performances, workshops, and student showcases.
  - **Value to the User:** This section is vital for building credibility and visual excitement. It allows users—especially prospective clients and event planners—to easily see the high-quality, professional standard of the dancers and the company's vibrant style before they commit to booking a class or requesting a quote.
    <img width="797" height="655" alt="Screenshot 2025-10-27 141457" src="https://github.com/user-attachments/assets/7a70e44d-5c63-4f22-9185-86d89c8c63c0" />


- **The Footer (Contact Section)**
  - The footer includes essential contact information—location, email, and WhatsApp number — along with the Instagram social link (powered by Font Awesome). **All contact elements are live**, actionable links that simplify user interaction: the address connects directly to a map, the email opens a mail client, and the WhatsApp number initiates a chat message.
  - **Value to the User:** This provides crucial accessibility and promotes instant communication, ensuring users can connect with the company effortlessly via any preferred method (navigation, email, chat, or social media).
    <img width="1219" height="88" alt="Screenshot 2025-10-27 140936" src="https://github.com/user-attachments/assets/5fb8684f-5dcf-443c-b8f8-962f94c73388" />


### Features Left to Implement (Future Plans)

- **Dynamic Class Filtering:** Implement JavaScript to allow students to filter the class schedule table by Day or Instructor, improving usability for large class rosters.
- **Image Gallery Filter:** Add filtering buttons (e.g., "Costumes," "Workshops," "Performances") to the `gallery.html` page to enhance the user's ability to browse visual content.

---

## 3. Testing

Comprehensive testing was performed to ensure the site is functional, responsive, and aesthetically consistent across platforms.

### Functionality and User Goal Testing

* **Navigation:** All internal anchor links (e.g., `#classes`, `#events`) and external links (social media, booking pages) were verified to ensure correct redirection.
* **Responsiveness:** The site was tested across mobile, tablet, and desktop viewports to confirm the **Bootstrap grid** correctly stacks and resizes content, particularly the multi-column sections (About Us, Classes) and the table layout.
* **Form Redirection:** The CTAs were tested to ensure they correctly send the user to the `booking.html` and `quote.html` forms. The **form `method="GET"`** structure was verified to pass parameters to the success pages, proving readiness for dynamic processing (see Unfixed Bugs).

### Validator Testing

* **HTML**
  * No errors were returned when passing the code through the official W3C validator.

* **CSS**
  * No errors were found when passing the custom CSS through the official (Jigsaw) validator.

* **Lighthouse & Accessibility**
  * The site was tested using Google Chrome's Lighthouse tool across all main pages.
  * The project achieved exceptional Lighthouse scores, confirming commitment to best practices and performance:
  * The high Accessibility score confirms the appropriate use of semantic HTML, sufficient color contrast, and correct heading structures, ensuring the site is highly usable for individuals with varying needs.
 
    <img width="643" height="188" alt="Screenshot 2025-10-27 141714" src="https://github.com/user-attachments/assets/f6f09fd8-331c-42fd-b7a1-68bfb911fe96" />



### Unfixed Bugs

* **Data Display on Success Pages:** The submitted form data **cannot be dynamically displayed** on the `success-page.html` or `quote-success.html` using only HTML and CSS. This limitation is inherent to the front-end-only constraint of the project. A note is included on the success pages to explain that displaying the data requires an additional layer (JavaScript) to read the URL parameters.

---

## 4. Deployment

The site was deployed using **GitHub Pages**, providing a simple and robust hosting solution for this static project.

The deployment steps were as follows:

1.  In the GitHub repository, navigate to the **Settings** tab.
2.  In the GitHub Pages section, the **Master Branch** was selected as the deployment source.
3.  Upon selection, GitHub automatically deployed the site and provided the live URL.

The live link for the project can be found here: \[ https://crucioltheresa.github.io/barefeet/index.html ]

---

## 5. Credits

### Content

* The company mission and ethos text were **original content** created to reflect the specified Brazilian-Middle Eastern fusion theme.
* The class schedule and instructor names are **fictional** for demonstration purposes.
* The icons in the footer and the "Learn More" icon were sourced from **Font Awesome**.

### Media

* All images used for the Hero, About Us, Events, and Classes sections were original photographs (proprietary content), ensuring full licensing and creative control.
* The logo image (assets/images/logo.png) is a custom graphic designed specifically for the Barefeet Dance Company brand.

### Code

* The implementation of the **Bootstrap 5.3** framework was used for all responsive grid, navigation, and component styling.
* The JavaScript code block at the bottom of index.html, used to ensure the Bootstrap mobile navbar collapses when navigating to in-page anchor links, **was adapted from the Love Running project structure.**
* The core implementation of the Events Carousel was based on the standard Bootstrap component, **with structural reference taken from the Boardwalk project example.**
