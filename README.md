## Commands to run the app locally
```
nvm use 16.16.0

Define the env variables in the .bashrc:
export MONGODB_DB_NAME=database_name_here
export MONGODB_CLUSTER_ADDRESS=cluster_address_here
export MONGODB_USERNAME=user_here
export MONGODB_PASSWORD="password_here"
export PORT=8080

source ~/.bashrc
Confirm if the variables were set successfully:
printenv MONGODB_DB_NAME

npm ci
npm start & npx wait-on http://127.0.0.1:$PORT
npm test
```
