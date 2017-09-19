# FaceChat
FaceChat is an mobile application that is designed to resolve an existing issue with the current dating apps out in the market today.

This app will, at a minimum, satisfy the following criteria with smooth, bug-free navigation, adequate seed data and sufficient CSS styling:

### Main MVPs
- [ ] Login using Facebook API User Auth
- [ ] Access Token created with Login  creates User State within our own app
- [ ] Series of questions after user creation(Preferences, location, push notifications)
- [ ] User is allowed to upload an profile image, design their profile(Profile Setup)
- [ ] Male vs Female profile design
- [ ] Browse(Bagel), discover function
- [ ] Video Scheduling function
- [ ] Chat interface
- [ ] Video Chat interface
- [ ] Production README

## How It All Works (rough draft)
  1. Users will login through Facebook, upon login a series of questions will pop up, sex preferences, location, notification, age preferences, height preferences
  2. Afterwards they will be prompted to set up their profile. This includes profile picture, height, ethnicity, religion, occupation, education, as well as answering questions like: I am ..., I like..., I appreciate when my date..., and their Briggs Meyer's Personality type
  3. The matching algorithm is inspired by the popular dating app 'Coffee meets Bagel', where matches will be based on individuals who have mutual acquaintances, this cannot be unlocked however
  4. There will be a discover function that will search for matches outside of their mutual group where individuals are connect with one another
  4. Limits to 25 new people a day
  5. Once a match is found, a scheduling interface will appear, two individuals will be put in an allotted time where they are both free. (Matched individuals will not be able to talk to each other until through video for the first time)
  6. Video chat commences and ends
  7. Feedback post-video chat (How much you enjoyed speaking with this person, would speak again, etc) This will not be shown to the other pair**
  8. Text Chat opens up to see if the two matched individuals want to continue talking, exchange information or schedule another video chat



## Technologies (subject to change)
Our mobile application will be using the MERN web stack. These frameworks stand for MongoDB, Express, React-Native, Node.js We will also be using Redux with React-Native.

## Implementation Timeline
This app will be a multi-month project, that will most likely up take longer then the expected timeline to fully polish and send to app store.

### Phase 0: Learning MongoDB, Node.js, Express, React-Native (one week)
**Objective:**
  - To understand new software libraries/technologies

### Phase 1: Backend Auth and Backend Setup(two weeks)
**Objective:**
  - Implement auth using Node.js with MongoDB as the Database
  - Implement User state, important information to display

### Phase 2: Front End(two weeks)
**Objective:**
  - Implement front end using React-Native, Redux

### Phase 3: UX, UI Design and polish(one week)
**Objective:**
  - To satisfy a smooth, bug-free user experience

## Potential Challenges
  - Facebook API with our own Auth
  - Video Chat & Text Chat
  - Match Algorithms
