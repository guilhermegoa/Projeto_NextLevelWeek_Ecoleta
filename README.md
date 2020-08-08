# Projeto_NextLevelWeek_Ecoleta

Rocketseat 2020 next_level_week_1 project.

#### Web screens

<img src="./images/web-1.png" width="300" height="150" /> <img src="./images/web-2.png" width="300" height="500" />

#### Mobile screens

<img src="./images/mobile-1.jpeg" width="200" height="400" /><img src="./images/mobile_selection_state.jpeg" width="200" height="400" /><img src="./images/mobile_selection_city.jpeg" width="200" height="400" />

<img src="./images/mobile-2.jpeg" width="200" height="400" /> <img src="./images/mobile-3.jpeg" width="200" height="400" /> <img src="./images/mobile-4.jpeg" width="200" height="400" /> <img src="./images/mobile-5.jpeg" width="200" height="400" /> <img src="./images/mobile-6.jpeg" width="200" height="400" />

<img src="./images/mobile-7.jpeg" width="200" height="400" /> <img src="./images/mobile-8.jpeg" width="200" height="400" /> <img src="./images/mobile-9.jpeg" width="200" height="400" />

## Project

##### Required

- Install [Node js](https://nodejs.org/en/)
- Install [yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable)
- Expo app, if running a mobile project

**_To download the entire repository_**

> git clone --recurse-submodules https://github.com/guilhermegoa/Projeto_NextLevelWeek_Ecoleta.git

### Server

- Open the Ecoleta_server folder
- To be open, you need to access the src folder, change the BASE_URL in the ".env" file. For that you must get the machine's ip, in the terminal:

  > ipconfig

  <img src="./images/ipconfig.png" width="500" height="400" />

- Copy the Ipv4 an change in the .env file as shown:

  > Susbstitua na BASE_URL no arquivo .env
  > http://{Ipv4}:3333  
  > Ex: http://192.168.1.103:3333

* With the terminal open, execute the commands:

  > yarn install

  > yarn knex:migrate

  > yarn knex:seed

* To start the server

  > yarn dev

**_Ok, now just run the web or mobile project._**

### Web

- In the terminal open folder Ecoleta_web and run command

  > yarn install

- To start the project web

  > yarn start

### Mobile

- To run the mobile it necessary install the expo-cli, with command:

  > yarn global add expo-cli

- Now, open mobile folder. Go to src/services, open api.ts file and change the BASE_URL.

  > http://{Ipv4}:3333  
  > Ex: http://192.168.1.1:3333

- After that, in the terminal open the mobile folder and run commands:

  > yarn install

  > yarn start

- After opening the expo's web page select LAN in the CONNECTION section to the run app in phone.
  <img src="./images/mobile_connection.png" width="300" height="50" />

- Open the expo app in phone and scan QRCode.
