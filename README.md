
<h1 align="center">
  <br>
  <a href="https://code-collab-pink.vercel.app"><img src="./public/title.png" alt="Code-Collab" width="400"></a>
  <br>
  Collabify
  <br>
</h1>

<h4 align="center">A collaborative coding platform where users can create virtual rooms, code together in real-time using an integrated IDE, built on top of <a href="https://microsoft.github.io/monaco-editor/" target="_blank">Monaco Editor</a>.</h4>

<!-- <p align="center">
  <a href="https://badge.fury.io/js/electron-markdownify">
    <img src="https://badge.fury.io/js/electron-markdownify.svg"
         alt="Gitter">
  </a>
  <a href="https://gitter.im/amitmerchant1990/electron-markdownify"><img src="https://badges.gitter.im/amitmerchant1990/electron-markdownify.svg"></a>
  <a href="https://saythanks.io/to/bullredeyes@gmail.com">
      <img src="https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg">
  </a>
  <a href="https://www.paypal.me/AmitMerchant">
    <img src="https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&amp;style=flat">
  </a>
</p> -->

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#setup">Setup</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#connect">Connect</a>
</p>


## Key Features

* Real-Time Collaboration - Make changes, See changes
  - Code together seamlessly with live updates, breaking geographical barriers for efficient teamwork.
* Multi-Language Support
  - Code in your language of choice; our platform supports a diverse range of programming languages for project development.
* Live Output Preview
  -  Instantly visualize code changes with live output preview, streamlining debugging and accelerating development.
* Create and Join Rooms
  - Establish focused coding spaces with dedicated rooms, enhancing communication and organization for collaborative coding.
* Dark/Light mode
* Compiler 
  - Compile and execute code in compiled languages with ease.
* Supports multiple cursors

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone frontend repository
$ git clone https://github.com/Dev-the-coder/Collabify.git

# Go into the repository
$ cd Collabify

# Install dependencies
$ npm install

# Run the app
$ npm run dev

# Now clone backend repository
$ git clone https://github.com/Dev-the-coder/Collabify-server.git

# Go into the repository
$ cd Collabify-server

# Install dependencies
$ npm install

# Run the app
$ npm run dev
```

> **Note**
> You need to run these servers concurrently. You can do this by opening multiple terminals or multiple code editors.


## Setup

Add following environmental variables 

- Server

```Plaintext
 # Sample .env file

  - JWT_SECRET = "dlfsxxxx"
  - JWT_EXP = "5d"
  - ROOM_JWT_EXP = "2d"
  - POSTGRES_PRISMA_URL = "postgress://xxxxxxxx"

```

- Client

```Plaintext
 # Sample .env file

  - NEXTAUTH_SECRET = "dlfsxxxx"
  - HACKEREARTH_CLIENT_ID = "dfsdxxxx"
  - HACKEREARTH_CLIENT_KEY = "hjhjhxxxxx"
``` 

## Tech-Stack

This software uses the following softwares-

- [Node.js](https://nodejs.org/)
- [Next.js](https://nextjs.org/)
- [Prisma ORM](https://www.prisma.io/)
- [Tailwind](https://tailwindcss.com/)

## Connect

- [Devesh](https://www.linkedin.com/in/devesh-gupta-464260218/)

