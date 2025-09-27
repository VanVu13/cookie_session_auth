# Cookie Session Auth

## Author
- Student ID: 22685821
- Fullname: Trịnh Văn Vũ

## How to Run
1. Install dependencies:
npm install
2. Run the project:
node `app.js`

## API Testing with Postman
### 1. Register
- Open Postman.
- Send POST request to `/register` with required data.
![register](public/results/register.png)
- Check database to confirm new user is created.
![register](public/results/user_mongodb.png)

### 2. Login
- Send POST request to `/login` with registered credentials.
![login](public/results/login.png)
- Check cookie
![login](public/results/cookie_postman.png)
- Check database to confirm session is created.
![login](public/results/sessions_mongodb.png)

### 3. Profile
- Endpoint: GET /profile
![profile](public/results/profile.png)

### 4. Logout
- Send GET request to `/logout`.
![logout](public/results/logout.png)
- check cookie delete in mongodb
![logout](public/results/cookie_delete_in_mongodb.png)
