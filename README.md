<p align="center"><img src="https://pbs.twimg.com/profile_images/1041540742940770304/Q-HPWlSn_400x400.jpg" width="200" /></p>

# JR JS Engineer - Test Project

Create a basic job listing board, with infinite scroll.

## User stories

Both of these user stories should be possible.

##### Employee

1.  Can see a list of jobs
2.  Can apply for a job
3.  Jobs they applied for are marked as "applied"

##### Employer

1.  Can post a job
1.  Can see jobs they posted (as well as others)
1.  Can see everyone who applied to jobs they posted

##### Both Users

1.  Can additionally see a list of GitHub jobs in the sidebar.

## Requirements

### UI / UX

1.  Job Listing Form
    * Title
    * Category
    * Budget
    * Description
1.  Job Listing Table
    * Show all relevant data from form
    * Indicate if a user applied
    * Infinite scroll
1.  Job Listing - Users who applied
    * Show available user info & when they applied
1.  Sidebar
    * List 10 Github jobs (from [Jobs API](https://jobs.github.com/api))

#### Packages to use

_Note: The use of additional packages is perfectly fine and in some cases encouraged, as long as they fall under the MIT license_

* [React](https://reactjs.org/)
* [Redux](https://github.com/reduxjs/redux)
* [Redux Saga](https://github.com/redux-saga/redux-saga)
* [Firebase](https://firebase.google.com/)
  * Firestore: data storage
  * Authentication: user authentication
* [Material UI](https://material-ui.com/)
  * Used for building your UI components

### Bonus Tasks

* First and foremost, have fun and leave your mark on the project!
* Find a good use for [firebase functions](https://firebase.google.com/docs/functions/) and/or any other server side function using [express](https://github.com/expressjs/express)
* Use [react-router](https://github.com/ReactTraining/react-router)
* Make sure the data persists
* Implement a "next" button in sidebar, to see the next 10 GH Jobs
* Customize material ui theme
