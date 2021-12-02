# Oh my food

## Table of content

- [Technical Informations](#1-technical-informations)
  - [Requirements](#11-requirements)
  - [Setup](#12-setup)
    </br></br></br>

## 1. Technical informations:

### 1.1 Requirements

![HTML](https://img.shields.io/badge/HTML-5-red)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![SASS](https://img.shields.io/badge/SASS-brightgreen)

Optionnal : ![NodeJS](https://img.shields.io/badge/NodeJS-16-yellow)
</br></br></br>

### 1.2 Setup

The project depends on certain modules to be able to compile and auto prefix the .scss files.
To be able to do so:

- If you use VSCode, you can use the Live SASS Compiler Extension by Glenn Marks ( forks of the one from Ritwick but uptodate).
- The project provide a package.json. Just run this command to install the dependencies:

```bash
npm install
```

or

```bash
yarn
```

Then run the start script to enable the live scss compiler and prefixer.

```bash
npm run start
```

or

```bash
yarn start
```
