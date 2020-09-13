# Snitch

Someone else suffers for your incompetence. Just like in real life!

# Background

I'm building a product for myself. I've only really been able to develop habits by adding external accountability—sticks, rather than carrots—so I'm building a lightweight web application to simulate that process.

# Project Goals

* Solidify programming, problem-solving, and web development lessons learned from Launch School's Programming and Backend [curriculum](https://launchschool.com/courses)
* Learn how to use external APIs
* (Stretch) Learn how to implement a relatively secure user registration, login, and authentication process

# (Projected) User Experience

1. User indicates a habit they would like to develop.
2. User indicates at what cadence that habit should be performed, e.g. daily, on certain days, weekends.
3. User indicates for how long the habit should be tracked, with a minimum of 21 days.
4. User indicates at what time the app should check to see if the habit was performed.
5. User nominates an accountability partner.
6. A text is sent to the nominated partner.
7. Nominated partner confirms participation. (or not, lol)
8. User receives a text at stated cadence at given time asking if the habit was performed that day.
9. If user answers yes, no text is sent to accountability partner. If user answers no, the application "snitches" on the user to their partner.
10. Process repeats until the user achieves the habit goal, cancels the goal, or the friendship with the partner terminates. (maybe because of the app, lol)

# Architecture

## Major Elements

* GUI
* Application Server
* Relational Database

## Technologies Used

* Ruby, along with other related frameworks and tools, like Sinatra, Puma, etc.
* [PostgreSQL](https://www.postgresql.org/)
* [Heroku](https://www.heroku.com/)
* [Twilio API](https://www.twilio.com/docs/usage/api)

# Updates

* 2020-09-13: README created.
