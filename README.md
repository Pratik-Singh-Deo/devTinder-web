# DevTinder

- Created a Vite + React application
- Remove unnecessary code and create a Hello World app
- Install Tailwind CSS
- Install Daisy UI
- Add NavBar component to App.jsx
- Create a NavBar.jsx seperate Component file
- Install react router dom
- Create BrowserRouter > Routes > Route=/Body > RouteChildren
- Create an Outlet in your Body Component
- Create a footer
- Create a Login Page
- Install axios
- CORS - install cors in backend => add middleware to with configurations: origin, credentials: true
- Whenever you're making API call so pass axios => {withCredentials: true}
- Install react-redux + @reduxjs/toolkit - https://redux-toolkit.js.org/tutorials
- configureStore => Provider => creteSlice => add reducer to store
- Add redux devtools in chrome
- Login and see if your data is coming properly in the store
- NavBar should update as soon as user logs in
- Refactor our code to add constants file + create a components folder

- You should not be able to access other routes without login
- If token is not present, redirect user to login page
- Logout feature
- Get the feed and add the feed in the store
- Build the user card on feed
- Edit profile feature
- Show Toast message on save of profile
- New Page - See all my connections
- New Page - See all my Connection Requests

# Body

Navbar
Route=/ => Feed
Route=/login => Login
Route=/connections => Connections
Router=/profile => Profile
