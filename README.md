#iXperience Learning Management System

[![Build Status](https://semaphoreci.com/api/v1/projects/3fe0a74a-4166-4205-967a-30d9fa97f990/575093/shields_badge.svg)](https://semaphoreci.com/ixperience/ixstudents)

### Starting Development

1. Pull/clone the repo.
2. Set the appropriate env variables, or ask for a copy of the the `.env` file. 
3. run `bundle`
4. run `rake db:prepare`
5. Start testing environment with `guard`. 
6. In a separate tab, run `heroku local -p 3000` to start the web and worker servers. Port default is 5000 without `-p 3000`.

To reset your database for testing/dev purposes run `rake db:reset`