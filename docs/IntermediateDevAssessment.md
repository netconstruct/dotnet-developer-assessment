<img src="../images/iDHL-DarkBlue.svg" alt="IDHL Logo" title="IDHL" width="90">

# Intermediate Developer Assessment

## Overview

You will create a blog post page using ASP.NET MVC. The focus is on demonstrating your fundamental skills in MVC, data handling, and basic front-end development.

## Objectives

1. ASP.NET MVC skills
1. Routing and controllers
1. Creating a service layer demonstrating SOLID principles
1. Basic CSS and responsive layout
1. Data retrieval and persistence with caching
1. Form input and validation (client-side and server-side)

## Exercises

### Exercise 1

Develop an MVC view that displays the blog post content, utilising the layout provided in the [template.html](./assets/template.html) file.

Move the [Blog-Posts.json](./assets/Blog-Posts.json) file to an appropriate location in the project for reading and writing data. Replace the section marked `<!--Blog post content-->` with the content from this JSON file.

Load a specific blog post from the JSON file based on its ID, employing MVC routing and the appropriate controller actions. For example: /blog/1/, /blog/2/, /blog/\<ID\>/, etc.

Additionally, demonstrate the use of dependency injection, service or repository patterns, and caching techniques to enhance code maintainability and performance.

### Exercise 2

Display a list of comments related to the blog post, sourced from the JSON file. Add this content to the section marked `<!--Blog post comments-->`.

### Exercise 3

In the section marked `<!--Blog post comment form-->`, add a comment form that allows users to submit comments, which will be stored against the relevant blog post item in the Blog-Posts.json file.

Form fields:
- Name (required)
- Email address (required)
- Comment (required)

### Exercise 4

Implement the functionality to reply to a comment. Save the reply in the appropriate section of the JSON file and display it directly underneath the comment to which the user has responded.

### Exercise 5 (Optional)

Incorporate a file upload feature that allows users to attach files to their comments. The uploaded files should be stored separately from the JSON file, while a reference to each file should be captured within the JSON data.

### Exercise 6 (Optional)

Create a blog listing page that displays basic blog cards for each post, with each card linking to the corresponding blog post. If time permits, implement pagination to enhance navigation through the blog posts.