# SwiftUI-Test-MVVM-Architecture

<img width="811" alt="Screenshot 2024-02-02 at 4 52 33 PM" src="https://github.com/vlaskos/SwiftUI-Test-MVVM-Architecture/blob/main/test.jpg">

<br>
- The requirement is to create an MVVM app project consuming the Github public API https://api.github.com/users where it has the ability to list all the Github users. 
- In first page,login screen, with fields for a nickname, password, and a login button. Simply add a delay of a few seconds to simulate the login process, then transition to the main screen as root.
- In second page, list all the Github users displaying their username and the github profile url below. Once the user clicks a username, he should be able to redirected to detailed page to display the avatar, username and the github profile url (html_url). 
- When a user clicks a github profile url it will open external browser to load the url.

## What do we want to assess?

1. Reuse example of arhitecture in this repo https://github.com/vlaskos/SwiftUI-Test-MVVM-Architecture/tree/main/MVVM.Demo.SwiftUI
2. Main goal to develop app based on MVVM pattern with Combine, SwiftUI, URLSessions.
3. Minimum deployment version - iOS 16.0.
4. Feel free to modify router, dependency modules.
5. Follow Swift coding style and convention

## Bonus points

- Write a networking layer with async/await
- Added paginations of 10 users per page

Source architecture https://github.com/jasonjrr/MVVM.Demo.SwiftUI/tree/master
