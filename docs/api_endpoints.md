# API Endpoints

### Session
* `POST /api/session`
* Creates new session on user login
* `DELETE /api/session`
* Deletes session on user logout

### Users
* `GET /api/users`
  * Users index/search
* `POST /api/users`
  * Creates new user
* `GET /api/users/:id`
  * Fetches single existing user profile
* `PATCH /api/users/:id`
  * Allows user to update their profile

### Boards
* `GET /api/users/:id/boards`
  * Fetches all boards on user profile
* `GET /api/users/:id/boards/:id`
  * Fetches a specific board that belongs to the user  
* `POST /api/users/:id/boards`
  * Creates new board on user profile
* `DELETE /api/users/:id/boards/:id`
  * Deletes board on user profile

### Pins
* `GET /api/users/:id/pins`
  * Fetches all pins created by the user
* `GET /api/users/:boardName/pins`
  * Fetches all pins for specific board
* `POST /api/:userName/:boardName/pins`
  * Creates new pin on user board
* `DELETE /api/pins/:pidId`
  * Deletes pin
