# Sign Up
 * As an unregistered user, I want to be able to create an account using a sign up form.
   * While on the `/signup` page:
      * I want to be able to input my email, username, and preferred password into the sign up form.
      * I want the website to log in me in after successfully completing the sign up form.
          * So that I can access the registered users functionality.
   * When I enter invalid data on the sign up form:
      * I would like to be informed of any invalid inputs and have the form repopulate my previous valid inputs (with the exception of my password).
          * So that I can reattempt the form validation process without having to re-enter valid data.

# Log In
 * As a registered user, I want to be able to log in with a login form.
   * While on the `/login` page:
      * I would like to be able to enter my username and password on a form.
      * I want the website to log in me in after successfully inputting valid information.
           * So that I can access the registered users functionality.
    * When I enter invalid data on the log in form.
      * I would like to be informed of any invalid inputs and have the form repopulate my previous valid inputs (with the exception of my password).
           * So that I can reattempt the form validation process without having to re-enter valid data.
    
# Demo User
 * As a unregistered user, I want to be able to easily locate the demo button on the `/signup` and `/login` pages so I can be allowed to use the site without the need of having to to register or log in.
    * When I'm on the `/login` or `/signup` pages:
        * I can click on a Demo User button to log me in and allow me access as a registered user.
             * So that I can demo the site's features and functionality without being hindered by additional registration requirements. 

# Log Out
 * As a logged in user, I want an easily accessible logout button on the nav bar.
     * While on any page of the site:
        * I can easily logout and be redirected back to the home page.
             * So that I can easily log out and keep my information secure.

# Cocktail-Q
  ### Create Cocktail-Q
 * As a logged in user, I want to be able to post new Cocktail-Q.
     * When I'm on the `/new-Cocktail-Q` page:
        * I can write and submit a new Cocktail-Q.
           * So that I can ask a question regarding my cocktail needs and desires.

  ### Viewing Cocktail-Q
  * As a logged in or logged out user, I want to be able to view a selection of the most recent Cocktail-Qs.
     * When I'm on the `/Cocktail-Qs` page:
        * I can view the ten most recently posted Cocktail-Qs.
             * So that I can browse through other users Cocktail-Qs.
  * As a logged in or logged out user, I want to be able to view a specific Cocktail-Q and its associated Cocktail-As and Cocktail-Votes.
     * When I'm on the `/Cocktail-Q/:id` page:
        * I can view the content of the Cocktail-Q, as well as the associated Cocktail-As and Cocktail-Votes.
             * So that I can read and vote on the Cocktail-Q of the selected question.
        * I can post a Cocktail-A to the associated Cocktail-Q if I'm a registered user.
             * So that I can answer a Cocktail-Q.
  ### Updating Cocktail-Q
  * As a logged in user, I have the capability to edit my Cocktail-Q by clicking an Edit button paired with the Cocktail-Q and anywhere that Cocktail-Q is showcased.
     * When I'm on the `/Cocktail-Q`, `/Cocktail-Q/:id`, or `/users/:id/Cocktail-Q `pages:
        * I can press "Edit" to make lasting changes to Cocktail-Q that I have written.
             * So that I can trim, add-on as I desired in my Cocktail-Q and fixed any error if need be.

 ### Deleting Cocktail-Q
 * As a logged in user, I want to have the ability to delete my Cocktail-Q by clicking a Delete button associated with the Cocktail-Q anywhere that Cocktail-Q is displayed.
    * When I'm on the `/Cocktail-Q`, `/Cocktail-Q/:id`, or `/users/:id/Cocktail-Q` pages:
         * I can click "Delete" to permanently delete a Cocktail-Q I have posted.
              * So that when I realize I shouldn't have publicly said something or think it has lost its relevancy, I can easily remove it.

# Cocktail-A
  ### Create Cocktail-A
 * As a logged in user, I want to be able to post new Cocktail-A to a specific Cocktail-Q.
     * When I'm on the `/Cocktail-Q/:id/create-answer` page:
        * I can write and submit a new Cocktail-A.
           * So that I can answer a question regarding someone's cocktail needs and desires.

  ### Viewing Cocktail-A
  * As a logged in or logged out user, I want to be able to view a selection of Cocktail-As related to a specific Cocktail-Q.
     * When I'm on the `/Cocktail-Qs/:id` page:
        * I can view the ten most upvoted Cocktail-As.
             * So that I can browse through other users Cocktail-As.

  ### Updating Cocktail-A
  * As a logged in user, I have the capability to edit my Cocktail-A by clicking an Edit button paired with the Cocktail-A and anywhere that Cocktail-A is showcased.
     * When I'm on the  `/Cocktail-Q/:id`, or `/users/:id/Cocktail-A `pages:
        * I can press "Edit" to make lasting changes to Cocktail-A that I have written.
             * So that I can trim, add-on as I desired in my Cocktail-A and fixed any error if need be.

 ### Deleting Cocktail-A
 * As a logged in user, I want to have the ability to delete my Cocktail-A by clicking a Delete button associated with the Cocktail-A anywhere that Cocktail-A is displayed.
    * When I'm on the `/Cocktail-Q/:id`, or `/users/:id/Cocktail-A` pages:
         * I can click "Delete" to permanently delete a Cocktail-A I have posted.
              * So that when I realize I shouldn't have publicly said something or think it has lost its relevancy, I can easily remove it.