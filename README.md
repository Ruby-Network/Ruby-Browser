<p align="center">
<img width="120px" src="https://github.com/Natant-Network/.github/raw/main/NATANT.png">
</p>

<h1 align="center">Natant Browser</h1>

### About
This is the official source code and repository for Natant Browser! This is Natant Networks *flagship* proxy!

### Developers
- [MotorTruck1221](https://github.com/motortruck1221) - Main Developer

### Setup
- Clone the repository
```bash
$ git clone https://github.com/Natant-Network/Natant-Browser.git
```
- Install the dependencies
```bash
$ npm install
```
- Setup your .env file
```bash
$ cp .env.example .env
```
- Change the port in the .env file to your liking
```bash
$ nano .env
```
- Start the server
```bash
$ npm start
```
#### Using docker and docker-compose
- Curl the docker-compose.yml file
```bash
$ curl -o docker-compose.yml https://raw.githubusercontent.com/Natant-Network/Natant-Browser/main/docker-compose.yml
```
- Chnage the port in the docker-compose.yml file to your liking
```bash
$ nano docker-compose.yml
```
- Start the server
```bash
$ docker-compose up -d
```
