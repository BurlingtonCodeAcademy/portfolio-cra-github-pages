# Portfolio Page

## Background

A **Personal Portfolio** is a web site that showcases your personal work.

It can serve as a resume that people can interact with to see examples of the work in question.

## Info

### The Portfolio Should Include

* Your full name
* Your Github username, with a link to your GitHub Repos page e.g. <https://github.com/BurlingtonCodeAcademy>
* Your public social media accounts, with links, e.g. <https://twitter.com/btvcodeacademy>
* Your LinkedIn account <https://www.linkedin.com/school/burlington-code-academy/>
* Your current home city and state. **do not** list your street address or zip code.
* How to contact you.
  * Consider what information you want to be available when anyone searches for your name.
  * Email, phone, other.

## Goals

* Understand and use the following:
  * Whitespace using margin and padding
  * Typography improvements
  * Text spacing
  * Color and contrast
  * Using images

## Stories

While the specific style choices and functionality are ultimately up to you, the following stories are required.

## Home Page

Should have:

* A profile image of you.
* A short description of who you are, for example:

> A passionate web developer looking to make a difference in Vermont.

* Links to the following sub-pages, which do not need to exist yet.
  * About Me
  * Projects or Portfolio
  * Hobbies and Interests
  * Work History
  * Contact Me Form

## About Me Page

* Build a page that includes basic details about your history as a person such as:
  * What interests you
  * Where you grew up
  * Why you got into programming

## Projects Page

* A list of all the repos on your personal github account
  * You can generate this using the [GitHub Rest API](https://developer.github.com/v3/repos/)
* Link to the completed or in progress project repositories for this bootcamp.
  * Use links to your github repositories and/or links to your deployed projects, possibly with cover screenshots.
  * Make sure the links are up to date!
* Add cover screenshots for each project.
  * Optionally add a separate page for each with a description of the objectives, your approach to solving the project, and anything else that you learned.
  * Optionally record a video showing your walk-through of the project program or application in use.

## Hobbies and Interests Page

* Hobbies
  * Do you play any instruments or play in a band?
  * Are you on a sports team like baseball, ultimate frisbee or softball?
  * Are you passionate about an outdoor sport such as skiing, rock climbing, mountain biking, kayaking or something else?
  * Do you volunteer at a local animal shelter, food shelf, or school board?

## Work History

* A web version of your resume with basic formatting. Make sure to include the following.
  * Your career goal(s).
  * Prior employers going back ten years.
  * Personal skills and experience.
    * e.g. HTML / CSS / JavaScript / Web Development / Git / Command Line

* Link to a downloadable version of your resume such as a PDF.

```html
<a href="/assets/my-resume.pdf" download>
  <img src="/images/my-resume-cover.jpg" alt="My Personal Resume Screenshot">
</a>
```

### Download File Example

* [Use the download attribute when linking to a downloadable file](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks#Use_the_download_attribute_when_linking_to_a_download)

## Navigation Bar

This should exist, and better yet *persist* across all other pages of your site.  

* Build a "Nav Bar" using a consistent UI on each page, with links to the various other pages of your portfolio.
* Style the navbar using Flexbox or CSS Grid.

### Example Navigation Elements

* Navigation <https://www.w3schools.com/css/css_navbar.asp>
* Drop Downs <https://www.w3schools.com/css/css_dropdowns.asp>
* Icon Navigation <https://www.w3schools.com/howto/howto_css_icon_bar.asp>
* Hamburger Menu Icon <https://www.w3schools.com/howto/howto_css_menu_icon.asp>
* Responsive Top Navigation <https://www.w3schools.com/howto/howto_js_topnav_responsive.asp>

## Page Footer

* Add a consistent, and better yet *persistent*, footer to your portfolio page which should include:
  * Contact Info
  * CopyWrite Info
  * Social Media Links
  * Basic links to other pages

### Footer Examples

* Sticky Footer Example <https://css-tricks.com/couple-takes-sticky-footer/>
* Basic Sticky Example <https://www.w3schools.com/howto/howto_css_fixed_footer.asp>

## Icebox

* Make the page mobile responsive
* Animate elements of your page
* Crete a sitemap for your site
* Host your site live on the internet

---

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

#### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

### Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

#### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

#### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

#### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

#### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

#### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

#### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
