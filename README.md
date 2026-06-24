# 🏏 Head and Tail Cricket Game

## Overview

Head and Tail Cricket Game is a desktop-based cricket simulation developed using C#, Windows Forms, ADO.NET, and SQL Server. The game is inspired by the popular hand cricket concept, where players compete by selecting numbers between 1 and 6 after a coin toss determines batting and bowling roles.

The application supports both singleplayer (Player vs Computer) and multiplayer (Player vs Player) modes. It automatically records match results, player scores, and performance statistics in a SQL Server database, providing an engaging and interactive gaming experience.

---

## Features

### 🪙 Coin Toss System

* Toss between Head and Tail to determine batting or bowling.
* Randomized toss logic for fair gameplay.

### 🏏 Singleplayer Mode

* Play against the computer.
* Computer generates random moves automatically.

### 👥 Multiplayer Mode

* Two players can compete on the same system.
* Real-time score comparison and winner determination.

### 📊 Score Tracking

* Automatic calculation of runs and wickets.
* Live score updates during gameplay.

### 📝 Match Recording

* Store match details in a SQL Server database.
* Maintain history of completed matches.

### 📈 Player Statistics

* Track player performance over multiple games.
* Store scores and match outcomes for analysis.

### 🖥 User-Friendly Interface

* Interactive Windows Forms GUI.
* Easy navigation and gameplay controls.

---

## Gameplay Rules

1. Players start with a coin toss (Head or Tail).
2. The winner decides whether to bat or bowl first.
3. Both players choose a number between 1 and 6.
4. If both numbers are the same:

   * The batsman is declared **Out**.
5. If the numbers are different:

   * The batsman's chosen number is added to the score.
6. The second innings begins after the first batsman is out.
7. The player with the higher score wins the match.

---

## Technologies Used

* C#
* Windows Forms
* ADO.NET
* SQL Server
* Object-Oriented Programming (OOP)

---

## Database Functionality

The system stores:

* Player Information
* Match Results
* Scores
* Match History
* Performance Statistics

Using ADO.NET for:

* Insert Operations
* Retrieve Operations
* Update Operations
* Delete Operations

---

## Concepts Implemented

### Windows Forms Development

Interactive desktop application with graphical user interface.

### ADO.NET

Database connectivity and CRUD operations.

### SQL Server Integration

Persistent storage of player and match records.

### Event-Driven Programming

Button clicks and game actions trigger gameplay events.

### Random Number Generation

Used for toss outcomes and computer-generated moves.

### Object-Oriented Programming

Structured classes and reusable game logic.

---

## Learning Outcomes

This project helped in understanding:

* Windows Forms Application Development
* ADO.NET Database Connectivity
* SQL Server Database Management
* CRUD Operations
* Event-Driven Programming
* Randomized Game Logic
* Object-Oriented Programming
* Game Development Fundamentals

---

## Future Enhancements

* Online Multiplayer Support
* Leaderboards and Rankings
* Multiple Match Formats
* User Authentication
* Sound Effects and Animations
* Tournament Mode
* Enhanced Statistics Dashboard

---

## Conclusion

Head and Tail Cricket Game combines simple cricket gameplay with database-driven record management. By integrating Windows Forms, ADO.NET, and SQL Server, the project demonstrates desktop application development, database operations, and game logic implementation in a fun and interactive way.
