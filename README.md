# Password Manager 

A Password Manager project created using the MERN stack. You can login and save your passwords. Passwords are saved in the database after AES encryption. So, your passwords are safe here. 

## Setting up the project

Go to the folder in which you want to clone the project and run the following command

```bash
git clone https://github.com/yashswi24/password-manager-mern.git
```

## Setting up the Server

To setup the server in your system run the following commands

```bash
cd server
npm install
```
After installing all the server dependencies run the server using the following command
```bash
npm run dev:start
```

Now, the server will be up and running

**Note :- You have to configure all the environment variables by creating a config.env file in root server folder.

Structure of the config.env file


```bash
DATABASE=<your MongoDB URI>
SECRET_KEY=<your secret key for hashing passwords>
CRYPTO_SECRET_KEY=<your secret key for encrypting passwords while saving in db>
```

## Setting up the Client

Go to the client folder and run

```bash
npm install
```
All the dependencies should be installed. Now, you just have to start the React server by following command
```bash
npm start
```
You also have to keep the mongodb cluster open in order to run the app properly.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.



