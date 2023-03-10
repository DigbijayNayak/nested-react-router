# Building Modern UIs with React Router v6
1. Routing Basics
    - The fundamental of routing
    - Install React Router DOM and connect to the browser's URL.
    - Configure your first route.
    - Use Link to navigate between pages.
    - Create a navigation with Link and Route.
2. Nested Routes and URL Parameters.
    - How nested routing works.
    - Create a 404 or No Match Route.
    - Define placeholders to create dynamic routes.
    - Read and display URL parameters.
    - Display active links.
    - Render a nested UI from route matches.
3. Take Routing Further
    - Index routes.
    - Navigate programmatically.
    - Pass data when navigating programmatically.
    - Pass location state.


# Routing Basics
- Single Page Applications
    A single webpage that runs in the browser and looks and functions like a multipage application.
- Routings
    The process of navigating users between different parts of the application when they visit a specific URL.
    Routing Features:
    - Keep track of browser history.
    - Link users to specific sections of an app.
    - Handle redirecting when user perform certain actions
- Where Can You use React Router?
    - On the web
    - On the server with Node.js
    - On mobile devices with React Native
- React Router DOM
    Includes the core functionality of React Router and DOM-specific APIs, components, and Hooks to implement dynamic routing in web application.
- Link
    Changes the URL and navigates to another view without reloading the page.
    - Link and Route Challenge
    1. Create a link for /home
    2. Create a link for /about
    3. Declare a route that renders `<About>` when the path is /about
    4. Place the Header and Nav in a new Header component

- URL Parameters
    URL parameters act as placeholders that match a specific portion of a URL.
- useParams()
    - A React Router
    - Hook to access URL parameters within a component
- Render a Nested UI
    - Define a route that renders the `<Session>` component when the URL is "categories/:catId/:sessionId"
    - Make each session a link that displays as the active link when clicked.
    - Instruct React Router where to render `<Session>` inside `<Category>`
    - Use the React Router Hook that returns the :catId and :sessionId parameters from the current URL.
- useNavigate()
    A Hook that lets you navigate programmatically
- useLocation()
    Returns a location object containing information about the current URL
- Pass Location State
    - Collect a name in the registration form
    - Pass the value of the name input to the Confirmation component via location state.
    - Display the submitted name in the confirmation message.

## Installing
1. To use these exercise files, you must have the following installed:
	- [Node.js](https://nodejs.org/en/)
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.
3. Run `npm install` to install all project dependencies, then `npm start` to run and launch the app
4. [Exercise Files](https://github.com/LinkedInLearning/building-modern-uis-with-react-router-v6-2495079)

### Instructor

Guil Hernandez 
                            
Software Development Instructor and Developer

