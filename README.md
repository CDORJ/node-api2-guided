# Node API 2 Guided Project Starter Code

Guided project starter code for **Node API 2** module.

In this project we will learn how to create a very simple Web API using `Node.js` and `Express`, and cover how to use `Express Routers` to break up the application to make it more maintainable.

## Prerequisites

- a REST client like [insomnia](https://insomnia.rest/download/) or [Postman](https://www.getpostman.com/downloads/) installed.

## Project Setup

- [ ] clone this repository.
- [ ] **CD into the folder** where you cloned the repo.
- [ ] type `npm i` to download dependencies.

Please follow along as the instructor builds the API step by step.

### restful vs non-restful endpoints
-Use this table to contrast RESTful endpoints from non RESTful counterparts.
-The verb should not be in the URI - that's what the HTTP verbs are for.

| Not using REST      | Using REST                                  |
| ------------------- | ------------------------------------------- |
| `/listAllHubs`      | GET /hubs                                   |
| `/createHub`        | POST /hubs                                  |
| `/updateHub`        | PUT /hubs/:id                               |
| `/deleteHub`        | DELETE /hubs/:id                            |
| `/listHubMessages`  | GET /hubs/:id/messages                      |
| `/countHubMessages` | GET /hubs/:id/messages as an extra property |


## Files with Notes:
- ./index.js
- ./server.js
- ./hubs/hubs-router.js
- ./messages/messages-router.js
- ./Express Router.mp4