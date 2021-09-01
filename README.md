# Makers Twitter Spring Boot Seed

You can use this seed to get started building a Twitter clone.

It comes set up with:

* The JUnit5 test framework.
* The Spring Boot web framework.
* The PostgreSQL database.
* The JPA ORM
* The Thymeleaf view templating system.

Posting and listing tweets is already implemented and commented.

## Quickstart

First create the databases.

```shell
; createdb makers-twitter-clone-dev
; createdb makers-twitter-clone-test
```

Then open this directory using IntelliJ. You may need to wait for
the dependencies to install.

Then, in the Gradle sidebar:

* To run the tests: `Twitter -> Tasks -> Verification -> Test`
* To run the server: `Twitter -> Tasks -> Application -> bootRun`

## Approach and Planning

### User Stories
```
TO BEGIN

As a user
So that I can know what website this is
I want to see the 'Twitter' heading on the home page

As a user
So that I can let people know what I am doing
I want to post a message (tweet) to twitter

As a user
So that I can see what others are saying
I want to see all tweets in reverse chronological order

As a user
So that I can better appreciate the context of a twitter
I want to see the time at which it was posted

As a user
So that I can post messages on twitter as me
I want to sign up for twitter
```
```
TO PROGRESS

As a user
So that only I can post messages on Twitter as me
I want to log in to Twitter

As a user
So that I can avoid others posting messages on Twitter as me
I want to log out of Twitter

```
```
TO ADVANCE

As a user
So that I can have a conversation
I want to reply to a tweet from another user

As a user
So that I can clearly read and use the service
I want to see a well-designed user interface
```

### Domain Model

<details>
<summary>Noun Owner/Property table</summary>
<br>
<img src="public/images/dm 1 java.png">
</details>

<details>
<summary>Action Owned by Table</summary>
<br>
<img src="public/images/dm 2 java.png">
</details>


<details>
<summary>Action Property Table</summary>
<br>
<img src="public/images/dm 3 java.png">
</details>

