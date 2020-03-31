# Professional Training and Development

"Organisations Achieve Greater Value throgh Professionally Coached Employees" - GaffCo Consulting Professional Communication Competence

[Professional Training and Development](https://naoisegaffney.github.io/Professional-Training-Development/index.html)

![Screenshot of the main page (index.html)](https://github.com/NaoiseGaffney/Professional-Training-Development/blob/master/docs/Screenshot%202020-03-30%2000.46.02.png)

A responsive website using only HTML 5 and CSS 3 to provide Training and Development, and Coaching opportunities to organisations and individuals.

## Business
### External Users' Goals
Clients and collaborators see the value provided in terms of a broad range of Training and Development, and Coaching opportunities.

Clients can book anything from single courses to fully bespoke programmes to suit their needs and requirements.

### Site Owner's Goals
As the programme owner I position my value and skills, as well as provide examples of programmes that I can provide to clients.

This enables me to reach a broader and global clientele that I would struggle to reach without an Internet presence such as this website.

### Potential Features
Display a slection of courses, programmes, and coaching for organisations and individuals.

View existing and bespoke courses, programmes and coaching opportunities for organisations and individuals.

Check next course dates and available times, and find the "course centre" (currently my home).

Book courses (yet to be implemented using JavaScript and Python 3). Courses are currently booked via the footer middle links (Mobile, WhatsApp, Email, LinkedIn, YouTube).

## Processes
### UX

The website provides a responsive and easy-to-use visual design, based on a good representation of the elements, and with intuitive navigation.

The website follows a hub-and-spoke Information Architecture though is flat which makes it easy to navigate between the "spokes".

There are three main actors/roles that will use the services provided by the website: Client, Collaborator, and Individual.

* As a client I want to improve the knowledge, skills, and attitude of my employees so that the performance of my organisation is greatly improved.
	* As a client I want to view the training and development, and coaching opportunities provided by GaffCo Consulting so that I can plan the training and development plans of my employees.
	* As a client I want to book the relevant programmes for the training and development for my employees so that they can perform better on-the-job.
	* As a client I want to contact the owner (Naoise Gaffney) to discuss the details of the programmes so that I can plan the continued development of my employees.

* As a collaborator I want to work with the owner (Naoise Gaffney) so that we can provide bespoke or off-the-shelf training and development opportunities to our clients.
	* As a collaborator I want to view the training and development, and coaching opportunities provided by GaffCo Consulting so that I can plan the training and development plans for my clients.
	* As a collaborator I want to book the relevant programmes for the training and development of my clients so that I can provide professional skills. training.
	* As a collaborator I want to contact the owner (Naoise Gaffney) to discuss the details of the programmes so that I can plan the continued development of my clients.

* As an individual I want to improve my professional skills so that I can perform better on-the-job.
	* As an individual I want to view the coaching opportunities provided by GaffCo Consulting so that I can improve my professional skills.
	* As an individual I want to book the relevant coaching opportunities provided by GaffCo Consulting so that I can improve my professional skills.
	* As an individual I want to contact the owner (Naoise Gaffney) to discuss the details of the coaching opportunities so that I can improve my professional skills.

Balsamiq wireframes and mockups of the website (simplified views, and not complete representations):

[Wireframe Diagrams of the Website](https://github.com/NaoiseGaffney/Professional-Training-Development/blob/master/docs/User-Centric%20Front-End%20Development%20Project%201.pdf)

## Solution
### Features

The website enables clients (corporate and individuals) and collaborators to view and book training and coaching opportunities to suit their training and development needs.

The website provides the owner with a global on-line presence, and an ability to position and prove the value of the training and development services provided.

The website provides multiple communication channels, enabling both direct and indirect communication between clients, collaborators, and owner.
 
#### Existing Features
#####These features are shared across all web pages on the website:

- Right-top Hamburger-menu: allows users to select the most suitable training and development, and coaching opportunity by having them click on the hamburger-menu and susbequent menu choice (Home, Organisations, Individuals, Programmes).
- Fixed footer - Professional Trainer and Coach: allows users to read my resumé to add to the websites credibility ("been there, done that, have the t-shirt") by clicking on the graduation-cap or text link or tool-tip.
- Fixed footer - Copyright 2020 GaffCo Consulting: allwos users to navigate to my "training centre (home)" by clicking on the location-arrow or text link or tool-tip.
- Fixed footer - Mobile (phone-call): allows users to call me on their mobile or via Skype for Business (if installed) to talk to me about training and development, and coaching, by clicking on the FontAwesome phone icon.
- Fixed footer - WhatsApp (message): allows users to WhatsApp message me on their mobile or laptop/desktop (if installed) to message me about training and development, and coaching, by clicking on the FontAwesome WhatsApp icon.
- Fixed footer - Email (message): allows users to Email me on their mobile or laptop/desktop (if mailto: is linked) to message me about training and development, and coaching, by clicking on the FontAwesome Email icon.
- Fixed footer - LinkedIn (website --> message): allows users to send me a LinkedIn message about training and development, and coaching, by clicking on the FontAwesome LinkedIn icon.

The Fixed footer FontAwesome icons zoom-in (transform: scale (1.5)) when hovered over, while also featuring a tool-tip (i[tool-tip]) to provide additional information. This is shared across all web pages on the website.

#####These features are unique or different on the web pages across the website:

The [Homepage: index.html](https://naoisegaffney.github.io/Professional-Training-Development/index.html) provides the following features:

- Background image: Emotional image of success after a hard run - sets the tone of the website, "You too will be equally successful and elated after attending our courses!"
- Motivational mission statement "Organisations Achieve Greater Value through Professionally Coached Employees" - sets the tone of the website stating of a fact, the real reason users are visiting this website.

The [Organisations page: organisations.html](https://naoisegaffney.github.io/Professional-Training-Development/organisations.html) provides the following features:

- Organisations: allows users to know they're on the Organisations page, and presents them with two menus, one for Professional Courses and the other for QQI Courses.
	- Organisations H1 with FontAwesome fa-sitemap icon makes it clear on which page the user is on.
	- Professional Courses Flex Div provides the relevant clickable course options.
	- QQI Courses Flex Div provides the relevant clickable courses.
- Clickable Course Links: allows users to view course details, dates, and training location, by clicking on each link/course item.
- Course Modal: allows users to view course detials and either book a course or close the modal by clicking on the 'Book Now!' button or the closing 'x'.

The [Individuals page: individuals.html](https://naoisegaffney.github.io/Professional-Training-Development/individuals.html) provides the following features:

- Individuals: allows users to know they're on the Individuals page, and presents them with two menus, one for Professional Skills Coaching and the other for Specific Coaching Occasions.
	- Individuals H1 with FontAwesome fa-user icon makes it clear on which page the user is on.
	- Professional Skills Coaching Flex Div provides the relevant clickable course options.
	- Specific Coaching Occasions Flex Div provides the relevant clickable courses.
- Clickable Course Links: allows users to view course details, dates, and training location, by clicking on each link/course item.
- Course Modal: allows users to view course detials and either book a course or close the modal by clicking on the 'Book Now!' button or the closing 'x'.

The [Programmes page: programmes.html](https://naoisegaffney.github.io/Professional-Training-Development/programmes.html) provides the following features:

- Individuals: allows users to know they're on the Individuals page, and presents them with two menus, one for Professional Skills Coaching and the other for Specific Coaching Occasions.
	- Individuals H1 with FontAwesome fa-user icon makes it clear on which page the user is on.
	- Professional Skills Coaching Flex Div provides the relevant clickable course options.
	- Specific Coaching Occasions Flex Div provides the relevant clickable courses.
- Clickable Course Links: allows users to view course details, dates, and training location, by clicking on each link/course item.
- Course Modal: allows users to view course detials and either book a course or close the modal by clicking on the 'Book Now!' button or the closing 'x'.

#### Features Left to Implement
- 'Book Now!' button function (JS) or --> Form (JS/Python 3).
- Additonal depth of detail for each course, for example Planned Learning Outcomes.

## Technology

A list of the languages, frameworks, libraries, and other tools used for this project.

* [HTML 5.2. - W3C Recommendation, 14 December 2017](https://www.w3.org/TR/html52/)
	* The project uses HTML 5 to create the content.
* [CSS 3 CSS - Snapshot 2018 W3C Working Group Note, 22 January 2019](https://www.w3.org/TR/css-2018/)
	* The project uses CSS 3 to style the content and provide the layout.
* [GitHub / GitPod /Git / GitHub Pages](https://github.com/)
	* The project uses GitHub:
		* GitPod to create and edit the project files (HTML 5 and CSS 3).
		* Git to add, commit, and push the project files to GitHub.
		* GitHub Pages turns GitHub Repositories into Websites.
* [Visual Studio Code](https://code.visualstudio.com/)
	* Code writing and staging. Went over to Visual Studio Code for improved coding ease, performance, and stability (used Repl-it~ and GitHub first).
* [Google Fonts: Raleway](https://fonts.googleapis.com/css?family=Raleway%7C&display=swap)
	* Using this font in different sizes for all text.
* [FontAweseome CDN](https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css)
	* Using FontAwesome font icons to add visual elements to key website features, making the website memorable and easier to navigate
* [Pixabay Free Images: Mountains](https://cdn.pixabay.com/photo/2019/01/27/22/32/mountains-3959204_1280.jpg)
	* Using this image as the background image througout the website.
* [CSS Before and After pseudo elements explained - part two: the content property by Kevin Powell](https://www.youtube.com/watch?v=xoRbkm8XgfQ)
	* Using the hover tool-tip function for the fixed footer FontAwesome icons: resumé, social and contact links, and location.
* [Pure CSS Hamburger Menu & Overlay by Traversy Media](https://www.youtube.com/watch?v=DZg6UfS5zYg)
	* Using the described hamburger menu function for my menu.
* [Target Modal from W3Schools](https://www.w3schools.com/cssref/tryit.asp?filename=trycss3_target_modal)
	* Using this modal function for my course details.
* [Strong Black French Press Coffee](https://www.youtube.com/watch?v=st571DYYTR8)
	* Keeps me alert and on-schedule; keeps me going through the night. This is the secret source of my programming-powers. :-)

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

HTML and CSS Validation: [Nu HTML and CSS Checker](https://validator.w3.org/nu/)

CSS Check!

HTML:

* index.html: Error: Attribute tool-tip not allowed on element i at this point.
* organisations.html: Error: Attribute tool-tip not allowed on element i at this point.
* individuals.html: Error: Attribute tool-tip not allowed on element i at this point.
* programmes.html: Error: Attribute tool-tip not allowed on element i at this point.

The "Error: Attribute tool-tip not allowed on element i at this point." errors are not important as the tool-tip function is best attached to the FontAwesome icons to provide the required functionality.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

git add .
git commit -m "..."
git push
...
enable GitPages


## Credits
![GaffCo Consulting Logo](https://github.com/NaoiseGaffney/Professional-Training-Development/blob/master/docs/GaffCo%20-%20Background.png)

### Content
- GitHub Pages: [https://naoisegaffney.github.io/Resume/index.html](https://naoisegaffney.github.io/Resume/index.html)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

I received inspiration for this project from X
Static front end project: Write custom HTML5 and CSS3 code to create a website of at least 3 pages, or (if using a single scrolling page), at least 3 separate page areas.

Information Architecture: Incorporate a main navigation menu and structured layout (you might want to use Bootstrap to accomplish this).

Documentation: Write a README.md file for your project that explains what the project does and the value that it provides to its users.

Version Control: Use Git & GitHub for version control.

Attribution: Maintain clear separation between code written by you and code from external sources (e.g. libraries or tutorials). Attribute any code from external sources to its source via comments above the code and (for larger dependencies) in the README.

Deployment: Deploy the final version of your code to a hosting platform such as GitHub Pages.

[mailto:naoise.gaff.gaffney@gmail.com](mailto:naoise.gaff.gaffney@gmail.com)
