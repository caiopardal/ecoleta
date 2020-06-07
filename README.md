<h1 align="center">
    <img alt="Ecoleta" title="#Ecoleta" src=".github/logo.png" width="300px" />
</h1>

<h4 align="center"> 
	Ecoleta 🚀
</h4>

<p align="center">
  <a href="#-nlw">Ecoleta</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-Technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-use">How to use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## :information_source: What's Ecoleta?

Ecoleta is an open source project that aims to connect people to companies that collect specific waste such as light bulbs, batteries, cooking oil, etc.  

## 💻 Project

In this repo, you'll find a mobile application where users will search for collection points and get in touch with them. A web application, where collection points can be registered and a back-end server that unifies both applications.

<h1 align="center">
    <img alt="Example" title="Example" src=".github/capa.svg" width="500px" />
</h1>

<div>
  <h1>Mobile</h1>
  <img alt="" title="Example" src=".github/inicio-mobile.svg" width="300px" />
  <img alt="" title="Example" src=".github/home-mobile.svg" width="300px" />

  <h1>Web</h1>
  <img alt="" title="Example" src=".github/banner.png" width="350px" />
  <img alt="" title="Example" src=".github/cadastro-web.png" width="300px" />
</div>


## :rocket: Technologies

This project was developed with the following technologies:

- [Node.js][nodejs]
- [TypeScript][typescript]
- [React][reactjs]
- [React Native][rn]
- [Expo][expo]

## 🔖 Layout

You can access the application layout here: [Figma](https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/).

## :information_source: How To Use

To clone and run this application, you'll need [Git](https://git-scm.com), [Node.js][nodejs] + [NPM][npm] installed on your computer.

From your command line:

### Install API 

```bash
# Clone this repository
$ git clone https://github.com/caiopardal/ecoleta

# Go into the repository
$ cd ecoleta/server

# Install dependencies
$ npm install

# Run Migrates
$ npm run knex:migrate

# Run Seeds
$ npm run knex:seed

# Start server
$ npm run dev

# running on port 5555
```

### Run Front-end

```bash
# Clone this repository
$ git clone https://github.com/caiopardal/ecoleta

# Go into the repository
$ cd ecoleta/web

# Install dependencies
$ npm install

# Run
$ npm start

# running on port 3000
```

### Run Mobile

```bash
# Clone this repository
$ git clone https://github.com/caiopardal/ecoleta

# Go into the repository
$ cd ecoleta/mobile

# Install dependencies
$ npm install

# Run
$ npm start

# Expo will open, just scan the qrcode on terminal or expo page

# If you have some problem with images inside the expo project, execute this project using:
$ npm start -c

# If you have some problem with fonts, execute:
$ expo install expo-font @expo-google-fonts/ubuntu @expo-google-fonts/roboto

```

## :memo: License

This project is under the MIT license. See the [LICENSE](https://github.com/DanielObara/NLW-1.0/blob/master/LICENSE) for details.


Made with ♥ by Caio Pardal 💻 [Get in touch!](https://www.linkedin.com/in/caio-henrique-pardal-2b7329166/)

[nodejs]: https://nodejs.org/
[typescript]: https://www.typescriptlang.org/
[expo]: https://expo.io/
[reactjs]: https://reactjs.org
[rn]: https://facebook.github.io/react-native/
[npm]: https://www.npmjs.com/
[vs]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[prettier]: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
