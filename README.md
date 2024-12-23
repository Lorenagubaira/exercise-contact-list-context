<!-- hide -->
# Contact Management Application 
<!-- endhide -->

Technologies: HTML, CSS, JS, React, React Router, and Context.

Hello! It is time to start doing professional front-end applications. This time
we will be creating a small contact management application that allows users to:
Read, Create, Update and Delete contacts. 

You may use this gif: [Check it out here!](https://github.com/breatheco-de/exercise-contact-list/blob/master/preview.gif?raw=true)

Or you can use these images:
[Image 1](https://github.com/breatheco-de/exercise-contact-list-context/blob/master/src/img/contact-list-1.png?raw=true) and
[Image 2](https://github.com/breatheco-de/exercise-contact-list-context/blob/master/src/img/contact-list-2.png?raw=true)

<onlyfor saas="false" withBanner="false">

## 🌱 How to start this project

Do not clone this repository because we are going to be using a different template.

We recommend opening the `react boilerplate` using a provisioning tool like [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recommended) or [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternatively, you can clone it on your local computer using the `git clone` command.

This is the repository you need to open or clone:

```text
https://github.com/4GeeksAcademy/react-hello-webapp
```

**👉 Please follow these steps on** [how to start a coding project](https://4geeks.com/lesson/how-to-start-a-project).

> 💡 Important: Remember to save and upload your code to GitHub by creating a new repository, updating the remote (`git remote set-url origin <your new url>`), and uploading the code to your new repository using the `add`, `commit` and `push` commands from the git terminal.

1. Install the `/node_modules`
   
```bash
$ npm install
```

2. Run the webpack development server

```bash
$ npm run start
```

This boilerplate contains no real functionalities, but it has 99.99% of the HTML/CSS that you'll need for the project, allowing you to focus on the functionality.

**Please use the Context for this project:** The boilerplate comes with the *Context* already configured. Check the `/store` folder.

</onlyfor>

## 📝 Instructions:

1. You have to add the code needed to make your application handle contacts, specifically: 
    - Create 
    - Update
    - Delete
2. (Optional) Ask the user for confirmation before deleting, use the Modal component for that.

All the functionalities must be implemented in the `actions` object inside the `flux.js` file.

`fetch` the data from the API: https://playground.4geeks.com/contact/docs

## This project is divided in: 

### Two different views: 

1. Contact: Contains the list of contacts.
2. AddContact: It's just a form used to create or update contacts.

### One component:

1. ContactCard: It just displays one contact.

## 💡 Hints:

+ Start with some dummy content in the store (`flux.js`).
  
+ Use Postman to try the API endpoints before coding.  

That is it! Start coding your React Application :)

This and many other projects are built by students as part of the 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) by [Alejandro Sanchez](https://twitter.com/alesanchezr) and many other contributors. Find out more about our [Full Stack Developer Course](https://4geeksacademy.com/us/coding-bootcamps/part-time-full-stack-developer), and [Data Science Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/datascience-machine-learning).
