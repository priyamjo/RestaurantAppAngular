# angular-project-ottomons
angular-project-ottomons created by GitHub Classroom

#### Website Link : https://ottomons-angular.cyclic.app/

# Harkanwal Grewal (N01494838): 
Frontend:
1: Created the basic structure of the app , on which team members can built their components.
2: Created the menu Page , to list all the items. 
3: Created the cart Page, to list all the items selected by the user as well as additional functionality to add/delete selected items.
4: Created order checkout page where user fills her/her address details in order to submit the order.
5: Implemented user,address,order details BehavioralSubject Service class in order to store the information globally and can be edited and altered by multiple pages.
6:Implemented routes functionality in the project  , in order to make it a multi page application. Also implemented Auth Guard to protect the routes from unauthorized access.
7: Used HttpModule to make HTTP requests, also used @input and @Output annotations to exchange the information between the components. 


# Kashish (N01569020):
Login Page - Designed Login page and added CSS styling along with angular.
Used UserService class to store the user information globally.
Used Http Module to make requests to the backend.
Used angular routing to route the user, according to the response returned by the backend.
Used conditional statements in angular to show the error messages to the user.
Jobs Page: Created Jobs API at the backend as well as the collection in the mongoDB.
Used the for loop to list all the available jobs.
Created Job interface in order to parse the backend response.


# Sonal Pooja (N01474010):

Designed a frontend for the Reviews and Contact Us pages.
Implemented forms on both pages to allow for user input.
Successfully retrieved static data from the backend for both pages.
Fetched the reviews data from the Reviews table using the backend API.
Added a Ratings table on the Reviews page, displaying ratings in the form of stars.
Added CSS styling for both the Reviews and Contact Us pages.
Understanding and implementing Angular's two-way data binding.
Learnt about Angular's HttpClient module for making API calls and handling HTTP requests.
Implementing forms in Angular for user input and handling form data.
Learnt about Angular's directives and services for extending component functionality.
Applying CSS styling to Angular components for better UI.

# Priya Joseph (N01468981):
Payment Page: 
Designed front end using angular and bootstrap.js
Once the address details are confimed, the order process reaches payment page where card name, number, expiry, cvv and card type is entered and validated using angular reactive forms and validators available such as touched, length etc. Once the form is validated, previously enetered address data and payment info is persisted into mongo DB using angular http post call. The user is then redirected back to home page.
Learnings - accessing data entered ina  different component and making an hhtp request with that data.
Learnt about BehaviorSubject
About us Page: The about us description is loaded using a service AboutService where the static data is stored.
