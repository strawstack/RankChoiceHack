# RankChoiceHack

A platform for Rank Choice Voting.

# Live Demo

[Live demo](https://rankify-app.netlify.app/)

# Layout of this Repository

This repository contains several directories and `index.html` files. The layout of the live site is the layout of the directories.

# Architecture

`Rankify` has a front-end that is a mix of `plain HTML` (inside index.html files), and `vanilla Javascript`. `Javascript` is used to connect with `Firebase Auth`, `Firestore`, and `populate the page` with the retrieved data.

# Firebase Auth

`Rankify` uses `Firebase Auth` to allow a user to sign-in as a guest (anonymous) or with their Google Account.

# Firestore

Data is retrieved from `Firestore` using Javascript and the `Firestore API`. Data (for example, a new Poll created by a user), is sent to `Firestore` for storage.

# Firestore Data Model



Polls 

# Host Your Own Version of this App

1. Create a Firebase Project.

2. Add `Sign-in with Google` and `Anonymous` as Authentication methods.

3. Add `Firestore` to your `Firebase` project.

4. Add two collections to `Firestore`: `Polls` and `Rankings`.

5. Host the repo on a server. Some options are: 

    - Locally, with `python3 -m http.server`
    - Online, with [Netlify](https://www.netlify.com/)