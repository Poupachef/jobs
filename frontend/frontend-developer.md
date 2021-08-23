# Cayena Frontend Challenge

### Instructions
- #### Import Postman files available in this folder for a list of all available endpoints.
- #### To avoid problems with tools versions, we recommended that you use an online version of Postman (https://web.postman.co/home). Import folder with postman files to set your environment and collection to access endpoints.
- #### Create a React project.
- #### Setup routing. (you application must have a spa behavior)
- #### Create a LOGIN page:
<p align="center"><img src="https://user-images.githubusercontent.com/22858307/107527240-685b9c00-6b97-11eb-80c4-f26a21b234a3.png" data-canonical-src="https://user-images.githubusercontent.com/22858307/107527240-685b9c00-6b97-11eb-80c4-f26a21b234a3.png" width="500" /></p>

    - Add user and password input fields.
    - Implement login using OAuth 2.0 authentication.
    - All HTTP requests must send the user's token inside the header.

- #### Create a LIST_SUPPLIERS page:
<p align="center"><img src="https://user-images.githubusercontent.com/22858307/107527245-698cc900-6b97-11eb-93e1-5fd011e7bf64.png" data-canonical-src="https://user-images.githubusercontent.com/22858307/107527245-698cc900-6b97-11eb-93e1-5fd011e7bf64.png" width="515" /></p>
    - Make a GET request to list all the registered suppliers.
    - When clicking on one of the suppliers, navigate to SUPPLIER_DETAIL page.
    - This page must be accessible only to authenticated users

- #### Create a SUPPLIER_DETAIL page:
<p align="center"><img src="https://user-images.githubusercontent.com/22858307/107527252-6a255f80-6b97-11eb-9dfe-a0ba2f65aa62.png" data-canonical-src="https://user-images.githubusercontent.com/22858307/107527252-6a255f80-6b97-11eb-9dfe-a0ba2f65aa62.png" width="515" /></p>

    - Make a GET request to get supplier details.
    - Create an update button to make a PUT request and update the current supplier.
    - This page must be accessible only to authenticated users

- #### Add a toggle switch to toggle the theme between dark and light mode, the new theme should be applied to all pages
- #### If the user's token expires, redirect to LOGIN page

### You may use
- Functional components and Hooks
- ContextAPI or Redux to handle the theme state
- Jest testing library (write unit tests for at least one component or module) 
- Lighthouse (ensure your app is compliance with rules of accessibility and best practices)
- Any package from NPM

### Bonus points
- SASS/LESS for styling
- CSS organization using BEM, SMACSS methodologies
- Typescript
- Configure webpack on your own (without CRA)

### Points evaluation
- Overall code organization and syntax
- Completion
- Architecture
- Security
- General UX (ex. action feedback)

If you have any questions, please contact us.