
## Features

- SignUp
- Login
- Game search : by title
- Game filter : editors choice
- Game sort : score



## Requirements

To Use the application please make sure node.js is install in your system.
    
## Folder structure

- backend (Consist of all the API & backend code)
- All other folders outside (Consist of all the frontend code)
## API Reference

#### SignUp API

```http
  GET /api/auth/createUser
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Name` | `string` | **Required**. |
| `Email` | `string` | **Required**. |
| `Password` | `string` | **Required**.  |

#### Login API

```http
  GET /api/auth/login
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Email` | `string` | **Required**. |
| `Password` | `string` | **Required**.  |

#### Get all games API

```http
  GET /game/fetchgames
```


## Run Locally

Install dependencies for backend

```bash
  npm install
```

Install dependencies for frontend 

```bash
  npm install
```

Run locally 

```bash
  npm run both
```

