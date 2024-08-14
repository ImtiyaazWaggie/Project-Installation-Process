# Project-Installation-Process

## Requirements

- Install Python: [Python Download Page](https://www.python.org/downloads/) [Rememeber when install python to check the box 'Add to Path']
- Intall Nodejs: [Nodejs Downloads Page](https://nodejs.org/en)

## Project Setup

- Download the project from the repo, now once you have it downloaded and opened up the project in Visual Studio Code. You can now open up the terminal in VSCode.

- Please use the Command Prompt(cmd) Terminal.
  
  ![CMD Terminal](https://github.com/user-attachments/assets/56c834a2-486a-4f41-ade7-38383dc15566)

### Installation  steps

1. Run the following command in the cmd terminal to create virtual environment in your project

  ```sh
python -m venv .venv
  ```
  
  ![Create Virtual Environment](https://github.com/user-attachments/assets/e48b8089-c3b5-4df1-a5d6-f39512b05edf)

  It will create a .venv folder for your virtual environment.
  
  ![Capture](https://github.com/user-attachments/assets/e5435f50-cd81-41f1-a511-022e692dda15)


  2. To activate the virtual environment, please run the following command in the cmd terminal

  ```sh
.venv\Scripts\activate
  ```

![Activate VE](https://github.com/user-attachments/assets/122af48c-61a1-47ad-a247-9b1cb3957296)


After you run the command you should see this:

![Active VE](https://github.com/user-attachments/assets/6e160a7d-db80-420c-87d7-91d4d15c63bd)


3. Time to install Flask. You can do that by running the following command

```sh
pip install Flask
  ```
 ![Install flask](https://github.com/user-attachments/assets/c6fc428e-85a1-4b9c-9d12-b540873af72c)

 After you install it should look like this, kinda:
![After install of flask](https://github.com/user-attachments/assets/be6901b6-268f-46c5-b920-3d5cffc46843)


## Time to install Tailwind css

1. Open a new termain and run the following command

```sh
npm install -D tailwindcss
  ```

 ![install tailwind css](https://github.com/user-attachments/assets/d30c23d6-c1c0-4970-a03e-8595bb4c88d5)

 After it should create a node modules foder in your 

![node modules](https://github.com/user-attachments/assets/511004d5-c400-4915-966c-b24c9f192053)


2. Run the following command to active a tailwindcss watch that will watch for any changes. Always run this when you starting up the project
```sh
npx tailwindcss -i ./flaskr/static/src/input.css -o ./flaskr/static/dist/css/output.css --watch
  ```
![tailwindcss watch](https://github.com/user-attachments/assets/ab561e30-555b-4294-b9ba-13290ed5b365)



## To create a database

1. Run the following command in the terminal to create the database
   
```sh
flask --app flaskr init-db
  ```
The following folder and files should be created

![database](https://github.com/user-attachments/assets/bbd470ba-3fb6-4259-8f81-e6721e0f7536)


## Now to run the actuall project

1. Run the following command in the terminal

```sh
flask --app flaskr run --debug
  ```

You should get the following:

![project run](https://github.com/user-attachments/assets/6435e329-deb7-4760-bba2-c8fe99c054b4)



All thats left is to run the link in the browser: 


```sh
http://127.0.0.1:5000
  ```








  
