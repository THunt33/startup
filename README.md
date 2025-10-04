# Startup - Fitness Website

[My Notes](notes.md)

## 🚀 Specification Deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] Proper use of Markdown
- [x] A concise and compelling elevator pitch
- [x] Description of key features
- [x] Description of how you will use each technology
- [x] One or more rough sketches of your application. Images must be embedded in this file using Markdown image references.

### Elevator pitch

Tired of guessing how many calories to eat or whether your workouts are actually building strength? My website is an all-in-one fitness hub that takes the guesswork out of achieving your goals. Whether you want to lose weight, gain muscle, or crush personal records, my platform calculates your exact calorie needs gives you the relevant information to do so. Track every lift, log your weights, and watch your progress soar. See your strength grow week after week and stay motivated with a roadmap to success.

### Design

![Design image](fit_web.png)

### Key features

-  Has a secure login over HTTPS
- Personalized calorie calculator for weight loss/gain goals  
- Strength training tracker with exercise database (track lifts, weights, sets/reps)  
- Progress dashboard with charts/graphs for calories and weight changes
- Personal Record tracking
- Leaderboard data of other users 
- Storage for all user progress and history  
- Ability to enter in data
- Display calculated data

### Technologies

I am going to use the required technologies in the following ways.

- **HTML** - Uses correct HTML structure for application. Two HTML pages for the login page and dashboard.
- **CSS** - Clean layouts for workout logs, charts, and forms. Styling that looks good on different screen sizes, uses good whitespace, color choice and contrast.
- **React** 
  - Calorie calculator form  
  - Progress dashboard with charts  
  - Routing between pages  
- **Service** - Backend service with endpoints for:
  - Login
  - Calculating daily calorie goals  
  - Saving/loading workout and weight data  
  - Getting progress history 
- **DB/Login** - Store users, workout logs (exercise, weight, reps) in database. Register and login users. User credentials securely stored in the database.
- **WebSocket** - Instant updates to charts when new data is logged and is shown to other users if permitted.

## 🚀 AWS deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] **Server deployed and accessible with custom domain name** - [My server link](https://thuntley.click).

## 🚀 HTML deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] **HTML pages** - Two HTML page that will let you login and get information from the dashboard.
- [x] **Proper HTML element usage** - I used header, footer, main, nav, img, a, input, button, form, and many more.
- [x] **Links** - The login and dashboard page both have links to each other to navigate the site. Also included a link to my GitHub repo in the footers.
- [x] **Text** - Instructions to login are on the login page. Additionally, a lot of text was needed on the dashboard page to guide the user and provide necessary information.
- [x] **3rd party API placeholder** - index.html has a place to display an inspirational quote below the personal records section
- [x] **Images** - Included images to both pages' headers.
- [x] **Login placeholder** - Input boxes and submit button for login.
- [x] **DB data placeholder** - Input box and 'calculate' button for calculator. Added input box and dropdown for Personal Records that pulls data from the database. The voting choices represent data pulled from the database.
- [x] **WebSocket placeholder** - The leaderboard section shows real-time data from accounts

## 🚀 CSS deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] **Header, footer, and main content body** - Implemented header with background, nice footer with proper spacing, and well-structured main content areas.
- [x] **Navigation elements** - Bootstrap nav, very nice.
- [x] **Responsive to window resizing** - All elements should scale properly and maintain usability.
- [x] **Application elements** - Styled all form elements, buttons, tables, and other components.
- [x] **Application text content** - Applied consistent fonts with proper hierarchy, appropriate sizing, and has good contrast.
- [x] **Application images** - Styled logo and images with proper sizing and consistent placement within the layout.

## 🚀 React part 1: Routing deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Bundled using Vite** - I did not complete this part of the deliverable.
- [ ] **Components** - I did not complete this part of the deliverable.
- [ ] **Router** - I did not complete this part of the deliverable.

## 🚀 React part 2: Reactivity deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **All functionality implemented or mocked out** - I did not complete this part of the deliverable.
- [ ] **Hooks** - I did not complete this part of the deliverable.

## 🚀 Service deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Node.js/Express HTTP service** - I did not complete this part of the deliverable.
- [ ] **Static middleware for frontend** - I did not complete this part of the deliverable.
- [ ] **Calls to third party endpoints** - I did not complete this part of the deliverable.
- [ ] **Backend service endpoints** - I did not complete this part of the deliverable.
- [ ] **Frontend calls service endpoints** - I did not complete this part of the deliverable.
- [ ] **Supports registration, login, logout, and restricted endpoint** - I did not complete this part of the deliverable.


## 🚀 DB deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Stores data in MongoDB** - I did not complete this part of the deliverable.
- [ ] **Stores credentials in MongoDB** - I did not complete this part of the deliverable.

## 🚀 WebSocket deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Backend listens for WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **Frontend makes WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **Data sent over WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **WebSocket data displayed** - I did not complete this part of the deliverable.
- [ ] **Application is fully functional** - I did not complete this part of the deliverable.
