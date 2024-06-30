# Online Electricity Billing application

This repository hosts the Online electricity bill payment application.

## Breakdown

I will be following a component based approach for the UI and then building the pages. The purpose of this approach is to experiment with the components at once and ensure UI consistency across the application.

After the components have been built I will simply integrate them into the application pages.

### Page priority

1. **Auth page:** This single page will serve login, sign up and account recovery.
2. **Landing page:** This page will have quick links to the payment screen & authentication page.
3. **User dashboard:** Admin and normal users will have the same dashboard page for managing their own connections. Before the user can perform any actions they'll have to complete all of their details.
   1. **Account Overview:** Will display user account
   2. **Bills**
   3. **Connections**
   4. **Help:** Help redirects to complaints and feedback. The content of the help page will be "Know your bill" which will display help for users to understand their bill like finding their CA number on the bill.
      1. **Complaints**
      2. **Feedback**
4. **Payments screen:** This page will support multiple payment methods. This will also allow for payments without login by simply accepting a contract account number.
5. **Manage:** This page is intended for the admin to manage user requests and other admin controls. This page will be based on what the user dashboard.
6. **Account Recovery**

### UI

#### Components

The components will have 2 phases:

1.  **Static**: Will only include HTML, Bootstrap & CSS
2.  **Dynamic**: If components need to be interactive then will use JavaScript here to make them interactive

Required components:

1. Navbar
2. Dropdown menu
3. Links
4. Forms
   1. Auth
   2. New connection
   3. Complaints
   4. Feedback
5. Popups: Notfications, ...
6. Dropdown list for selecting connection

#### Other

Some other things will be required to build the page like:

1. Fonts
2. Color palette
3. Transitions & Animations

For the color palette, I will be adding to the color palette as I build more components in the components playground page.
