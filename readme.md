There should be:

Admin accounts which are used to
signup/login
manage teams (add, remove, edit, view)
create fixtures (add, remove, edit, view)
Generate unique links for fixture
Users accounts who can
signup/login
view teams
view completed fixtures
view pending fixtures
robustly search fixtures/teams
Only the search API should be availble to the public.
Authentication and Session Management
Use redis as your session store.
Authentication and Authorization for admin and user accounts should be done using Bearer token and JWT.
Tools/Stack
NodeJs (TypeScript & Express) or Golang
MongoDB
Redis
Docker
POSTMAN
Tests
Unit tests are a must, submissions without tests will be ignored.

Submission
Your API endpoints should be well documented in POSTMAN.
Seed the db with lots of data before final submission.
Code should be hosted on a git repository, Github preferably.
The API should be hosted on a live server (e.g. https://heroku.com)
Your app should be containerized using docker.
Write e2e tests for all user stories
Implement web caching API endpoints using Redis.
Implement rate limiting for user account API access.



[tope]
for( user of users){

}
[
    {
        status: comp,
        type: good
    },
        {
        status: pending,
        type: v. good
    },
]