-React-phonebook-v3 repository created
-When running the task code, there are no errors or warnings in the console
-For each component there is a separate folder with the React component file and the style file
-PropTypes are described for components

Backend
There is a ready-made backend for this task. Familiarized with the documentation. It supports all necessary contact collection operations as well as user registration, login and update using JWT. I used it instead of the previous backend created through the mockapi.io service.

Routing
Added routing with the React Router library. The program has several pages:
/register - public route for registering a new user with a form
/login - public login route of an existing user with a form
/contacts - a private route for working with the user's contact list
Added a Navigation component with links for navigating routes.

User menu
Created a UserMenu component that displays the user's mail and a logout button. This is what its markup looks like.
<div>
   <p>mango@mail.com</p>
   <button>Logout</button>
</div>

Stylization
This is the final version of the program, so I worked on the design of the interface. Used the styling or component library, Chakra UI or Material UI.

