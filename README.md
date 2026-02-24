💻 How to run the app locally! 🏃

### STEP-1
- `cd frontend`
- `yarn install`
- `yarn start`

### STAP-2
- `cd backend`
- `yarn install`
- create folder `uploads`
- create `confilg` folder and a `.env` file
- use your Cradincial in.env file

```
PORT = 8000
DB_URL = ""
JWT_SECRET_KEY = ""
JWT_EXPIRES = 7d
ACTIVATION_SECRET = 
SMPT_HOST = 'smtp.gmail.com'
SMPT_PORT = 465
SMPT_PASSWORD = 
SMPT_MAIL =
STRIPE_API_KEY = 
STRIPE_SECRET_KEY = 
```
- `yarn start`

### STAP-3

- `cd socket`
- `yarn install`
- create a `.env` file
```
PORT = 4000
```
- `yarn start`
