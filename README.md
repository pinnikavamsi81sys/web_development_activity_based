# Web Development Projects
 Detail              Information
  ------------------- ------------------------------------------------------
  **Name**            Pinnika Vamsi Krishna
  **University**      Dr. RVR NRI University
  **Course**          B.Tech -- Computer Science and Engineering (AI & ML)
  **Academic Year**   First Year

------------------------------------------------------------------------


A collection of three introductory web development projects created
using **HTML5** and **CSS3** as part of the First Year B.Tech Computer
Science and Engineering (AI & ML) coursework.

The repository brings together three static webpages:

1.  **Explore Vijayawada** -- an informational webpage about places to
    visit, activities, and local food.
2.  **FITZONE Gym Website** -- a gym website presenting workout
    programs, trainer categories, membership plans, facilities, class
    schedules, and a registration form.
3.  **NRI College Webpage** -- a simple college welcome page with a
    navigation bar.

> **Project scope:** These projects are front-end practice projects. The
> supplied reports do not document a backend, database, JavaScript
> functionality, or a build system.

------------------------------------------------------------------------

## 1. Project Title

**Web Development Projects -- Explore Vijayawada, FITZONE Gym, and NRI
College**

## 2. Project Description

This repository contains three introductory webpages developed to
practise the fundamentals of HTML and CSS.

-   **Explore Vijayawada** introduces Vijayawada, Andhra Pradesh. It
    presents a welcome message, a photograph of Prakasam Barrage, a list
    of places to visit, suggested activities, and food items to try.
-   **FITZONE Gym Website** presents a gym's workout programs, trainer
    roles, membership options, facilities, weekly class schedule, and a
    front-end registration form.
-   **NRI College Webpage** displays the college name, a welcome
    message, and a simple navigation bar containing Home, About,
    Courses, and Contact links.

Each webpage has its own HTML and CSS files. The reports describe the
pages as rendered in a browser using the supplied local stylesheets. The
Explore Vijayawada page also uses a local image file named
`barrage.jpg`.

## 3. Project Objectives

The objectives of these projects are to:

-   Understand the basic structure of an HTML document.
-   Practise using semantic HTML elements such as `header`, `nav`,
    `main`, `section`, and `footer` where included in the source.
-   Apply CSS to control colours, typography, spacing, borders, and page
    layout.
-   Organise webpage content into readable sections.
-   Practise links, lists, cards, buttons, and form controls.
-   Explore CSS Grid, Flexbox, hover effects, and a media query in the
    FITZONE project.
-   Understand how a browser displays HTML together with a linked CSS
    stylesheet.

## 4. Features

### Explore Vijayawada

-   Header with the title **Explore Vijayawada** and a subtitle.
-   Welcome section with a Prakasam Barrage photograph and a short city
    introduction.
-   Places to visit:
    -   Kanaka Durga Temple
    -   Prakasam Barrage
    -   Undavalli Caves
    -   Bhavani Island
    -   Gandhi Hill
-   Things to do:
    -   Visit famous temples
    -   Enjoy a boat ride
    -   Explore historical monuments
    -   Enjoy river views
-   Food to try:
    -   Andhra Chicken Curry
    -   Gongura Pachadi
    -   Punugulu
    -   Andhra Meals
-   Closing footer message.
-   Blue colour theme with white content sections, borders, and rounded
    corners.

**Documented limitation:** The supplied page is static. It does not
include interactive navigation, buttons, hyperlinks, or forms.

### FITZONE Gym Website

-   FITZONE header and navigation links to Home, Programs, Trainers,
    Pricing, and Register.
-   Hero section with the heading **BUILD YOUR BEST BODY** and a **Join
    Now** button.
-   Three workout program cards: Strength Training, Cardio Fitness, and
    Yoga & Flexibility.
-   Three trainer roles: Strength Coach, Cardio Coach, and Yoga
    Instructor.
-   Three membership plans:
    -   Basic -- 999/- per month
    -   Standard -- 1,499/- per month
    -   Premium -- 2,499/- per month
-   **Choose Plan** links that point to the registration section.
-   Facilities listing: Modern Equipment, Locker Rooms, and Personal
    Training.
-   Weekly class schedule: Monday -- Yoga, Wednesday -- Cardio, and
    Friday -- Strength.
-   Registration form with name, email, phone, an additional text field,
    and a membership dropdown.
-   CSS card hover effects, button hover styling, and a media query for
    narrower screens.

**Documented limitations:** The registration form has no supplied
backend or form-processing endpoint, so submitted information is not
documented as being stored. The **Join Now** button is not connected to
a form or navigation action in the supplied HTML.

### NRI College Webpage

-   Header displaying **NRI college**.
-   Welcome message: **welcome to NRI college**.
-   Navigation labels: Home, About, Courses, and Contact.
-   Simple brown header and white navigation area.
-   Basic HTML structure and CSS styling.

**Documented limitations:** The navigation links use placeholder or
empty destinations. The supplied HTML does not include separate content
sections, images, buttons, a form, or a footer.

## 5. Technologies Used

  -----------------------------------------------------------------------
  Technology                          Usage
  ----------------------------------- -----------------------------------
  HTML5                               Creates the structure and content
                                      of the webpages.

  CSS3                                Controls colours, fonts, spacing,
                                      borders, layout, and visual
                                      presentation.

  Chromium browser                    Used to render the pages for the
                                      screenshots described in the
                                      project reports.
  -----------------------------------------------------------------------

Additional implementation details documented in the reports:

-   FITZONE uses CSS Grid, Flexbox, hover styling, and a media query.
-   Explore Vijayawada uses a local image named `barrage.jpg`.
-   No JavaScript framework, backend service, database, external image
    library, or external CSS library is documented for these projects.

## 6. Project Architecture

The projects use a simple static front-end architecture:

``` text
User
  |
  v
Web Browser
  |
  +--> HTML file
  |      |
  |      +--> Page structure and content
  |
  +--> Linked CSS file
  |      |
  |      +--> Colours, typography, spacing, and layout
  |
  +--> Local image (Explore Vijayawada only)
         |
         +--> barrage.jpg
```

Each project is opened directly in a web browser. The browser reads the
HTML file, applies its linked CSS stylesheet, and displays the page.

No server-side processing, database connection, or API integration is
described in the supplied reports.

## 7. Project Folder Structure

The reports identify the following source filenames:

-   Explore Vijayawada: `vamsi.html`, `vamsi.css`, and `barrage.jpg`.
-   FITZONE: `vamsi.html` and `vamsi.css`.
-   NRI College: `semantic.html` and `se.css`.

Because the first two projects use the same HTML and CSS filenames, keep
each project in a separate folder. The following is a **suggested
repository organisation**, not a claim about the original uploaded
folder structure:

``` text
web-development-projects/
│
├── Explore-Vijayawada/
│   ├── vamsi.html
│   ├── vamsi.css
│   └── barrage.jpg
│
├── FITZONE-Gym/
│   ├── vamsi.html
│   └── vamsi.css
│
├── NRI-College/
│   ├── semantic.html
│   └── se.css
│
├── screenshots/
│   └── Add exported project screenshots here
│
└── README.md
```

The HTML and CSS source listings are included in the uploaded project
reports, but the standalone source files and `barrage.jpg` were not
supplied as separate uploads for this README task. Add the actual files
to the corresponding folders before publishing the repository. The
reports contain rendered screenshots, but standalone screenshot image
files were not supplied.

## 8. Installation Steps

These projects use HTML and CSS and do not require package installation
or a build process.

1.  Install or use a modern web browser such as Google Chrome, Microsoft
    Edge, or Firefox.
2.  Download or clone this repository.
3.  Make sure the project files are placed in the folder structure shown
    above.
4.  For Explore Vijayawada, place `barrage.jpg` in the same folder as
    its HTML file.
5.  Open the required project folder.

To clone the repository, replace the example URL with the actual GitHub
repository URL:

``` bash
git clone https://github.com/<your-username>/<your-repository>.git
cd <your-repository>
```

No `npm install`, framework setup, or database configuration is
documented as necessary.

## 9. How to Run the Projects

### Option 1: Open directly in a browser

Open the relevant HTML file:

-   Explore Vijayawada: `Explore-Vijayawada/vamsi.html`
-   FITZONE Gym: `FITZONE-Gym/vamsi.html`
-   NRI College: `NRI-College/semantic.html`

You can also right-click the HTML file and choose **Open with** to
select a browser.

### Option 2: Run a local development server with Python

If Python is installed, open a terminal in the repository's root folder
and run:

``` bash
python -m http.server 8000
```

Then open this address in your browser:

``` text
http://localhost:8000
```

Select the required project folder and open its HTML file.

To stop the local server, press `Ctrl + C` in the terminal.

## 10. Input and Output Details

  -----------------------------------------------------------------------
  Project                 Input                   Expected browser output
  ----------------------- ----------------------- -----------------------
  Explore Vijayawada      The HTML page, linked   A destination
                          CSS file, and local     information page with a
                          `barrage.jpg` image.    header, welcome section
                                                  and image, lists of
                                                  places, activities and
                                                  food, and a footer.

  FITZONE Gym             The HTML page and       A gym information page
                          linked CSS file.        with navigation, hero
                          Visitors can enter      area, program and
                          values in the displayed trainer cards, pricing,
                          form fields and choose  facilities, schedule,
                          a membership option.    and registration form.

  NRI College             The HTML page and       A minimal college
                          linked CSS file.        welcome page with a
                                                  brown header and a
                                                  white navigation strip.
  -----------------------------------------------------------------------

**Important input/output notes:**

-   The FITZONE form contains required fields, but the supplied project
    does not document a server endpoint or data storage. Do not treat it
    as a working online registration system.
-   The FITZONE **Join Now** button is displayed as a call-to-action but
    has no implemented action in the supplied HTML.
-   The NRI College navigation labels are displayed, but their
    destinations do not lead to implemented page sections.
-   Explore Vijayawada needs the local `barrage.jpg` file to display its
    destination photograph correctly.

## 11. Screenshots / Output Images

The uploaded project reports include browser-rendered output
screenshots:

-   **Explore Vijayawada:** The report includes the rendered webpage
    from header to footer.
-   **FITZONE Gym:** The report includes three screenshots covering the
    webpage.
-   **NRI College:** The report includes one screenshot of the webpage.

The screenshots are embedded in the Word reports; separate screenshot
image files were not supplied. Export the screenshots from the reports
or capture fresh browser screenshots, then add them to the repository's
`screenshots/` folder.

After adding the image files, you can display them here by updating the
paths:

``` markdown
### Explore Vijayawada
![Explore Vijayawada webpage](screenshots/explore-vijayawada.png)

### FITZONE Gym Website
![FITZONE Gym Website - Screenshot 1](screenshots/fitzone-1.png)
![FITZONE Gym Website - Screenshot 2](screenshots/fitzone-2.png)
![FITZONE Gym Website - Screenshot 3](screenshots/fitzone-3.png)

### NRI College Webpage
![NRI College Webpage](screenshots/nri-college.png)
```

These are suggested image filenames. They will work only after you add
the corresponding images at those paths.

## 12. Future Enhancements

The following are possible future improvements. They are **not features
currently documented as implemented**:

-   Add functional navigation destinations and complete content sections
    to the NRI College webpage.
-   Connect the FITZONE **Join Now** button to the registration section.
-   Add backend form processing and secure storage if FITZONE
    registration is intended to collect real submissions.
-   Improve the FITZONE form by replacing the additional text field's
    placeholder with a meaningful label.
-   Add more information and useful links to the Explore Vijayawada
    webpage.
-   Add more destination images where appropriate.
-   Improve accessibility with descriptive image alternative text, clear
    form labels, and keyboard-friendly interactions.
-   Test the pages at different screen sizes and improve responsive
    layouts where needed.

## 13. Conclusion

These three projects provide practical experience with the fundamentals
of front-end web development.

**Explore Vijayawada** demonstrates how to present informational content
using headings, sections, lists, images, and CSS styling. **FITZONE
Gym** provides practice with navigation, cards, membership information,
form controls, CSS Grid, Flexbox, hover effects, and responsive styling.
**NRI College** demonstrates a basic webpage structure with a styled
header and navigation bar.

Together, the projects help build an understanding of how HTML defines
webpage structure and how CSS controls its visual presentation. They
provide a foundation for learning more advanced web development
concepts.



*Created as part of the First Year B.Tech CSE (AI & ML) web development
project work at Dr. RVR NRI University.*
