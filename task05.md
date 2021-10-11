Task 5 Use-case
======

Write 7 use-case scenarios, how user will interact with your application

Every use-case scenario should contain:

1) Name
2) Goal (what user trying to do)
3) Preconditions if applicable (e.g. user should be signed in)
4) Step-by-step script: what user doing and what he get (refer to your forms in task 3)

Example:

```
Scenario "Signing in"
Goal: Become authenticated user
Precondition: none

1) User opens page "<main page url>"
2) Main page is displayed to user
3) User clicks button "SIGN IN"
4) Sign in form is displayed to user
5) User enters correct value in `username` field
6) Entered value is displayed in field `username`
7) User enters correct value in `password` field
8) Entered value, which is masked with * , is displayed in field `password`
9) User click button "SIGN IN"
10) Form become blocked
11) Application send request to api method 'signIn'
12) Once result of request was got, application opens page "Todos list"
```
