# Ditto Social Media App (Spring Middle and Backend)
In this social network, everyone is friends with everyone. As a user, you will be able to register and login to your account. When you successfully login, you are automatically friends with everyone which means you will see a feed of everyone's posts. Users will be able to create a post and like other people's posts. Users will also have the ability to view other profiles which will display posts of that specific user.

# Technologies Used
* Spring MVC 
* PostgreSQL
* Angular 2+
* GCP Compute Engine
* GCP Cloud SQL
* Spring ORM
* Java

# Features
* Everyone is friends with everyone.
* Users can view a profile containing their information, profile picture, and posts.
* Users can search for friends by name (first or last) and view friends' profiles.
* Login and account registry features with SHA256 password hashing.
* Users can view a global feed containing posts from all registered accounts.
* Users can like posts. 
* Posts may contain multiple images as well as text.
* Password recovery by email.  
To-do List: 
* Allow users to make posts containing videos using YouTube's API.
* Allow users to comment on posts. 

# Getting Started
```
git clone https://github.com/fullxtilt/RevatureProj2-Spring.git
```
## Setup
Environment Variables:
* DITTO_DB_HOSTIP             | Database Host IP
* DITTO_DB_NAME               | Database Name
* DITTO_DB_USERNAME           | Username
* DITTO_DB_PASSWORD           | Password
* DITTO_SPRING_IP_AND_PORT    | IP and Port for Tomcat Server
* DITTO_ANGULAR_IP_AND_PORT   | IP and Port for Angular Server

# Usage
Create an account and then log in to access website functionality. Users can edit their profile information by clicking on their profile picture or the marker by their name and status. The button at the top left links to the global feed, while the 'Me' button links to a user's personal profile. Users can post using the '+' icon beside posts on their profile page. Users can search for friends' profiles using the search bar. 

# Contributors
Ryan Moss
John Benson
Jae Kyoung Lee (LJ)
Mike Keefer
