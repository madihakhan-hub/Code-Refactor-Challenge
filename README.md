# 01 HTML, CSS, and Git: Code Refactor - Module 1 Challenge

## Description

This week's Challenge is an on-the-job ticket&mdash;meaning that I will begin with a starter code that  I need to modify. 

**Refactoring** existing code (improving it without changing what it does) to meet a certain set of standards or to implement a new technology is a common task for front-end and junior developers. For this particular Challenge, a marketing agency has hired you to refactor an existing site to make it more accessible. 

> **Important**: When working with someone else's code, you should adhere to the **Scout Rule**&mdash;always leave the code a little cleaner than when you found it.

An increasingly important consideration for businesses, web **accessibility** ensures that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards. Accessibility is good for business&mdash;for one thing, accessible sites rank higher in search engines like Google. It also helps companies avoid litigation, which might arise if people with disabilities can't access a website.

Accessibility can include complex requirements, but your tech lead has given you a small list of specific criteria for this project. These criteria are documented in the Acceptance Criteria section.

To impress clients, you should always exceed expectations and improve the codebase for long-term sustainability. For example, check that all links are functioning correctly. You can also increase the efficiency of the CSS by consolidating the selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

Are you ready to begin? Here are this week's Challenge requirements.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Mock-Up

The following image shows the web application's appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./Assets/01-html-css-git-homework-demo.png)

> **Note**: This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px. Eventually you'll learn how to make elements responsive so that your web application is optimized for any screen size.

## Installation

Follow these instructions to create the project and deploy it to GitHub Pages:

1. Create a new repository on your GitHub account and clone it to your computer.

2. Once the repository is cloned, use VScode to open the "index.html" file to start editing by adding HTML semantics.

3. Add the 'header' element within the body. *make sure to add closing elements*

4. Add the 'nav' element under 'h1' for the navigation bar on the page. *Be sure to edit the CSS file for this step, otherwise the naviagation bar will display as a bulleted list on the left side under the Title.* ![image](https://github.com/madihakhan-hub/Wk-1-Challenge/assets/144630720/c4c8a988-9dc4-4eef-901d-7dc4f13e7325) ![image](https://github.com/madihakhan-hub/Wk-1-Challenge/assets/144630720/51b4f4b5-034d-4bfc-a669-25c51cbba51c)

5. For the images, amke sure to add the 'figure' element. In the opening element, be sure to include the id and class before adding the closing arrow. ![image](https://github.com/madihakhan-hub/Wk-1-Challenge/assets/144630720/4209a4a6-ce44-4cb5-b312-ab51aa88a506)

6. Add 'alt' attribute to describe the image, making it more accessible for all users who may not be able to view the image. ![image](https://github.com/madihakhan-hub/Wk-1-Challenge/assets/144630720/1c450929-a6f6-4ad6-9526-2705c4cd548a)

7. Add 'aside' element used for the textbox on the right side of the screen. ![image](https://github.com/madihakhan-hub/Wk-1-Challenge/assets/144630720/8f45d636-6ea7-474c-a743-7fea48cd7ae6)

9. Add 'footer' element. ![image](https://github.com/madihakhan-hub/Wk-1-Challenge/assets/144630720/7122fc9e-56b7-451c-8845-d217c95e51d3)

10. When you're ready to deploy, use the `git add`, `git commit`, and `git push` commands to save and push your code to your GitHub repository.

11. Navigate to your GitHub repository in the browser and then select the Settings tab on the right side of the page.

12. On the Settings page, select Pages on the left side of the page. On the GitHub Pages screen, choose `main` in the dropdown under Branch. Click the Save button.

13. Navigate to <your-github-username.github.io/your-repository-name> and you will find that your new webpage has gone live! For example, if your GitHub username is "lernantino" and the project is "css-demo-site", then your URL would be <lernantino.github.io/css-demo-site>.

> **Important**: It might take a few minutes for GitHub pages to display your site correctly. If your project does not deploy or display correctly, check that all file paths in your application are relative and use the right casing. GitHub is case-sensitive, an inccorect capital or lowercase letter could cause problems in deployment.

Be sure to add, commit, and push your work to see the most up-to-date version of your app!

