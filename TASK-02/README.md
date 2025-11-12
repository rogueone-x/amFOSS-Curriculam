# Software Requirement Specification (SRS)

## 1. Introduction

- Author : Aadith Anil
- Product : MeloFi

### 1.1 Purpose
The purpose of this document to breif the functional and non-functional aspects of MeloFi. This document explains the about the scope of the project, the functionalities the software provides and a breif its UI. It also mentions about the tech stack being used and possible future developments.

### 1.2 Intended Audience
The software is intended towards music lovers, people who want to explore new genres and artists and everyone who wants to have a great musical experience. In the Future, artists who want the expand the their horizon.

### 1.3 Project Scope
MeloFi is a simple, free and open-source music player app. It allows users to stream music, create playlists and control playback settings. Users can search for tracks, view info like artist, albumn, genre and control playback(pause, play, skip, volume).

## 2. Overall Description

### 2.1 Product Perspective
MeloFi will use APIs for streaming music. It will cache songs locally for playback when offline. In Melofi you can search for tracks and filter them based on genre, artist or ablumn. It also enables sorting on release dates and alphabetic order. The playback comes with options like pause, play, skip, progress bar, loop and shuffle (when playing a playlist). MeloFi also allows user to create and edit multiple playlists. The interface also enables both Dark and Light Mode.

### 2.2 Operating Enviroment
MeloFi will be available on both Andriod and Web.

## 3. User Interface

- A Login and sign up screen.
- Home -  With recommendations and recently played music.
- Search 
- Settings 
- Track Title Screen - with options to pause, play, skip, along with a progress bar.

## 4. Tech Stack

- Wireframe, Design - Figma
- Web
    - Frontend : React.js, Javascript
    - Backend : Flask and REST APIs, Python
- Mobile : Jetpack Compose, Kotlin

## 5. Future Scope

In the future, implemennting an AI based music recommendation system would improve the user experience significantly and deliver an overall better user experience. Also create an environment for artists to release their tracks.