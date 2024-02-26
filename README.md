# Youtube Backend

- This project is created while learning backend from Chai aur Javascript Backend series (Chai aur Code - Hitesh Choudhary).

## Fearures

implemented some youtube features like,

- Register User
- Login
- Logout
- Refresh Access Token
- Change User Details
- Watch History

Some features is not implemented yet. Ex:- video, like, comment, playlist, tweet etc.
In Future we will implement all.

## Getting Started

```js
npm i
npm run dev
```

Project will start on localhost:8000 port.

## Project Model

[youtube backend model](./src/youtube-backend.png)

## About

- In production grade application people generate complex string for ACCESS_TOKEN_SECRET and REFRESH_TOKEN_SECRET. we can generate from websites like sha256.
- REFRESH_TOKEN_EXPIRY is greater than ACCESS_TOKEN_EXPIRY.
- we not store access token. we store only refresh token.
