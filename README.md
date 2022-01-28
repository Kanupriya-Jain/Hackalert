# Hackio – a contests and hackathons reminder
## Problem Statement
There are a vast plethora of hackathons and coding contests happening every day on various platforms like codeforces, codechef, and many more. Sometimes it becomes very difficult for college students to keep track of all such opportunities. This challenge is faced by most students due to the availability of so many different platforms. At the end of the day, students often end up missing one or the other opportunity. 

## Proposed Solution 
This project proposes an app “Hackio” which will help the users to remain updated about different opportunities by showing all the ongoing and upcoming hackathons and coding contents in one single place with the help of different APIs. In this way, students can keep track of all the opportunities. Users can sign in using their Google account, view all the Ongoing and Upcoming contests, mark their calendars for the ones they are interested and get notified so that they don’t miss out on any opportunity.

  Splash Screen                 |   Navigation Drawer        |  Upcoming Hackathons
:-------------------------:|:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/81557355/151604197-530da875-8c8e-47d6-adbc-2ce535853c63.jpeg?raw=true)|![](https://user-images.githubusercontent.com/81557355/151606055-5048506e-b71a-4d46-9953-13325df8ebf3.jpeg?raw=true)|![](https://user-images.githubusercontent.com/81557355/151606095-742b5bb5-1bc6-4b70-b365-c76c7305e66e.jpeg?raw=true)


## Functionality & Concepts used

The App has an interactive interface which helps anybody to check for the upcoming and ongoing contests as well as the hackathons. Following are few android concepts used to achieve the functionalities in app:

- Sign in: Everybody has a google account so we have used firebase authentication to login with the google id and fetch details to build up your profile for the app which is displayed in the navigation drawer.
- Navigation drawer: a navigation drawer has been setup which makes it easy to toggle between different screens in the app. It also has developers’ sections with some basic info about the developers.
- Constraint Layout: Most of the activities in the app uses a flexible constraint layout, which is easy to handle for different screen sizes.
- RecyclerView: To present the list of different upcoming and ongoing contests and hackathons we used the efficient recyclerview. We are using an API to fetch the details regarding different contests and hackathons.
- Fragments: We have used fragments to display the ongoing and upcoming contests and hackathons under different tabs.
- MVVM based concepts used are - 
  - Coroutine scope used so that api calls on background thread 
  - Livedata and data binding: We are also using LiveData to update & observe any changes in the contests details at real time and update it in the app. 
  - Viewmodel is used so that activity do not destroy on orientation change or by going to home screen

## Future Scope

The app is currently in the Alpha testing phase. Once the app is fully tested, we plan to add more websites collaboration and also provide news of various upcoming hackthons and contest. We also plan to publish this app on the Google Play store after some refinments.

## Developers

- [@Akshay Kumar](https://www.linkedin.com/in/-akshay-kumar-/)
- [@Kanupriya Jain](https://www.linkedin.com/in/kanupriya--jain/)
- [@Akshit Tyagi](https://www.linkedin.com/in/akshit-tyagi-119027207/)
- [@Vaibhav Gupta](https://www.linkedin.com/in/vaibhav-gupta-451825200/)
- [@Aditya Yadav](https://www.linkedin.com/in/aditya-yadav-800a7a21a/)
