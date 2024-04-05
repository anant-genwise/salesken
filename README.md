# Space-X-Launches-App 🚀

Explore space missions with the SpaceX Launches App built with React Native. This app fetches data from the SpaceX API, displaying a visually appealing list of launches, complete with image, title, launch date, rocket details, and launch site information. Users can filter launches by year and status, search for launches by title, and experience real-time search results. The app also features a responsive design for iPhone XR, iPad Mini, and large screen sizes. State management is handled with Redux, including a simple authentication system with login and signup screens. Dive into the cosmos and stay updated on SpaceX launches!

How To Run The App:

1 While Running the application you should install node js in your system
after installing node js .
2 clone the repository.
3 open terminal.
4 Change the directory using the command cd from the terminal and cd till SpaceX.
5 After that run the command: npm i
6 After successfully installing node_modules folder in the project.
7 write a command: npx expo start
8 press w on the terminal to see the app on the web.

Features :


Part 1: UI/UX Implementation


• Implemented cards from the Spacex API
• Filter Functionality
Incorporates 2 filters on the launch list page:
Launch Year
Launch Status
• Search Functionality
Real-time display of search results as the user types the title name.
It is also case-sensitive.
• Responsive Design
iPhone XR (414 x 896)
iPad Mini (768 x 1024)
Large Screen Size (1024 x 471)

Part 2: State Management with Redux


• Implemented a straightforward authentication system with login and signup screens.
• The credentials I am saving in local storage
• Effectively manages loading and error states during the retrieval of data from the SpaceX API.
