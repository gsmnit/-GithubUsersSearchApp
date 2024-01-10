GitHub User Search App
Description
This app allows searching for GitHub users and viewing their profiles.

Features
Search for users by username
View user profiles with avatar, name, bio, followers and following count
Tap follower/following counts to view lists of users
Navigation stack to go back through views
Getting Started
This app was built using:

GitHub REST API
Kotlin + Java
Retrofit
RxJava - initial version
Kotlin coroutine - newer verison

Usage 
1. Clone this repo, Build and install the apk on android phone  
2. Type a username into the search bar to find a GitHub user. If the user doesn't exist, a "Not found" message is shown.

Profile View
If the user is found, their profile is displayed with:
Avatar image
Username
Name
Bio description
Follower count - tap to view followers list
Following count - tap to view following list
Followers/Following Lists
Tap the follower or following count to view a list of those users. Tapping on a user navigates to their profile.

Navigation
The back button navigates back through previously viewed screens.

Bonus Features (I am planning to add)
Skeleton loading state
Pull to refresh on profile view
Profile caching & cache invalidation

I am developing this project using these software architecture principals
1. Clean, readable, documented code
2. Adherence to SOLID principles
3. Usage of a clear architecture pattern
