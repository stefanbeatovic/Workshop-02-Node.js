
# Workshop 02 - Requirements

## Overview
This document describes the tasks for the Node.js HTTP server workshop.

Complete all **mandatory tasks**.  
Optional tasks are provided for additional practice.

---

## General Rules
- Work only inside the `starter/` folder
- Do not change the repository structure unless instructed
- Commit your work regularly with meaningful commit messages
- Do **not** commit `node_modules`

---

## Mandatory Tasks

### This is the link to the Render site: https://workshop-02-node-js.onrender.com/

### Task 1 - Start the Server
**Description**  
Start a Node.js HTTP server that listens on port 3000.

**Requirements**
- Use the built-in `http` module.
- Start the server with `server.listen()`.
- Print a message when the server starts.

---

### Task 2 - Add Routing
**Description**  
Send the user to the correct HTML file depending on the URL.

**Requirements**
- `/` must serve `index.html`.
- `/about` must serve `about.html`.
- `/contact` must serve `contact.html`.

---

### Task 3 - Serve HTML Files
**Description**  
Read the selected HTML file and send it back to the browser.

**Requirements**
- Use `fs.readFile()` to read the file.
- Return status code 200 when the file is found.
- Send the response with the correct HTML content type.

---

### Task 4 - Serve CSS Files
**Description**  
Serve CSS files from the `public/styles` folder.

**Requirements**
- Handle requests starting with `/styles/`.
- Use `text/css` as the content type for CSS files.
- Check the file path so requests cannot escape the public folder.

---

### Task 5 - Handle Errors
**Description**  
Show useful error pages when a page is missing or the server has a problem.

**Requirements**
- Return a 404 response for unknown routes.
- Serve the custom `public/404.html` page.
- Log server errors and serve the custom `public/500.html` page for 500 errors.

---

## Validation / Acceptance Criteria
Your solution will be considered complete if:
- The application runs without errors
- All mandatory tasks are implemented
- Code is readable and well-structured
- No unnecessary files are committed

---

## Optional Tasks (Bonus)
These tasks are **optional** and not required for completion.

- Add a `GET /api/time` route.
- Return the current date and time as JSON.
- Include both a readable date and a timestamp.

---

## Submission Checklist
Before submitting, make sure that:
- [x] All mandatory tasks are completed
- [x] Application starts successfully
- [x] Code is pushed to GitHub
- [x] Repository does not contain `node_modules`
- [x] README instructions were followed

AI disclaimer:

AI was used to support learning and understanding the Node.js server.js file codebase better. AI was also used to improve grammar check on my text files. The solution file was used at times to solve the workshop tasks, because I'm still new to some skills. I understand the codebase concepts, how it is formulated to develop the server-side static website with error handling, how http request-response cycle works, and how CSS styling is fetched with the security measures taken against attacks outside the specified file path etc. I also consulted colleagues when deploying Render, and got their help with it. 


---

## Evaluation Criteria (If Graded)
Your submission may be evaluated based on:
- Correctness of implementation
- Code quality and structure
- Proper use of Git
- Fulfillment of requirements

---

## Notes
- Ask questions if requirements are unclear
- Partial solutions may receive partial credit
- Late submissions follow course policy

---

Good luck! 💪
