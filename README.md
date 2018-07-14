# HTTP Routes

## Project Description
Building on the "Hello HTTP" lab, this project focuses on creating an HTTP server that exposes a REST API as the resource for the basic CRUD operations using end-to-end (E2E) testing.

## Developer
Requires:
* Node v10 or later.
* PostgreSQL 

### How to get started
* Fork repository, clone locally, navigate to repository directory,
* Download all the files with `npm i`,
* In Postgres, add a database titled `disneyparks`;
* To test, run `npm test`. 

### How to use API
* Connect to server with `npm run start`.
* Enter `http://localhost:3000` in your browser.

This API uses the following methods for the paths listed:

Method | Path
---|---
`GET` |     `/<resources>`
`GET` |     `/<resources>/:id`
`POST` |    `/<resources>`
`PUT` |     `/<resources>/:id`
`DELETE` |  `/<resources>/:id`

## Contributor
[Mariah Adams](https://github.com/MariahAdams)

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgment 
Forked from [alchemy-fullstack-js-summer-2018/http-routes](https://github.com/alchemy-fullstack-js-summer-2018/http-routes)