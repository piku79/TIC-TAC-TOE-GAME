<h1 align="center">TIC-TAC-TOE-GAME</h1>


## :rocket: Knowledges
 - `ReactJS`
 - `Framer Motion`

## :book: How to use
To clone and run this application, you'll need [Git](https://git-scm.com/downloads) and [ReactJS](https://react.dev/) installed on your computer. From your command line:

```
# Clone this repository
$ git clone https://github.com/ucfx/TIC-TAC-TOE-GAME.git

# Go into the repository
$ cd TIC-TAC-TOE-GAME

# Install dependencies
$ npm install

# Run the app
$ npm start
```
## :link: Demo
  - <a target="_blank" href="https://ucfx.github.io/TIC-TAC-TOE-GAME/"> Click Here </a> to see and play by yourself a demo of the game.

## :mailbox: Contact
  - <a target="_blank" href="mailto:ucefhammadi@gmail.com">E-mail</a>


Käivitamine:
Antud rakenduse käivitamise eelduseks on Dockeri olemasolu arvutis (https://docs.docker.com/get-docker/)

Alla tuleb laadida (soovitavalt pull käsuga) repositoorium
https://github.com/piku79/TIC-TAC-TOE-GAME.git

Seejärel liikuda vastavasse kausta (TIC-TAC-TOE-GAME) ning docker file käivitada:
docker run -dp 8000:3000 tictactoegame:latest

Rakendusele pääseb ligi brauserist http://localhost:8000/ või siis läbi Dockeri programmi.


Probleemid:
- Kogu linuxi ja serverite ja rakendusserverite teema on minu jaoks täiesti võõras, mistõttu kogu ülesanne oli minu jaoks paras probleem
- Dockeriga kokkupuudet varem polnud.
- Ei osanud forkida.
- Dockeri installeerimine oli millegipärast väga aeganõudev
- create-react-app react-docker-example --> bash: create-react-app: command not found - esimese hooga ei saanud aru, kuidas neid käskusid kasutada ega ka seda, et hiljem kasutati <> sulgusid näitena ning ise koodi kirjutades tuli need eemaldada
- node versiooni leidmine
- Probleemiks oli kogu protsess pärast dockerfile buildi
- Mingil põhjusel ei avanenud mäng, vaid brauser laadis ilmselt cashist mingi varasema tunni tulemuse.
- muud vist lisada ei ole.
