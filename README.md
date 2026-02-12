# 📱 CMPSC 131 Social Network Final Project

## 👤 Author

**Name:** Amogh Krishna Namuduri\
**GitHub:** AmoghNamuduri\
**Course:** CMPSC 131 -- Fall 2024

------------------------------------------------------------------------

## 📌 Project Overview

This project implements a **console-based social networking system**
using Python.\
It simulates basic social network operations such as user
authentication, friend management, and network analysis using core
computer science concepts like dictionaries, graph traversal, and
sorting algorithms.

The application loads user data from a file, encrypts passwords, and
allows users to interact with their social network through a menu-driven
interface.

------------------------------------------------------------------------

## 🚀 Features

### 🔐 User Authentication

-   Password encryption using a Caesar-style cipher
-   Secure login verification

### 👥 Friend Management

-   Add friends (mutual connection)
-   Remove friends
-   Prevent duplicate friendships

### 📊 Social Network Insights

-   Sort friend list based on common friends
-   Find nth-level friends using **Breadth-First Search (BFS)**
-   Count number of friends by country

------------------------------------------------------------------------

## 🧠 Computer Science Concepts Used

-   Dictionaries and Lists
-   File Handling
-   Encryption Basics
-   Error Handling using Error Codes
-   Bubble Sort Algorithm
-   Graph Traversal (BFS)
-   Data Structure Mutation
-   CLI (Command Line Interface) Design

------------------------------------------------------------------------

## 📂 File Structure

    Social_network.py     # Main application code
    users_small.txt            # Input file containing user data (required to run)

------------------------------------------------------------------------

## 📄 Input File Format

Each line in the input file must follow this format:

    username, password, bio, country | friend1, friend2, friend3

### Example:

    Amogh, pass123, Data Science student, USA | Alex, John
    Alex, hello123, CS major, Canada | Amogh
    John, test456, Gamer, UK | Amogh

⚠ Spaces matter in the formatting.

------------------------------------------------------------------------

## ▶️ How To Run

### 1️⃣ Clone Repository

``` bash
git clone <your-repo-link>
cd <repo-folder>
```

### 2️⃣ Run Program

``` bash
python Social_network.py
```

### 3️⃣ Enter File Path When Prompted

Example:

    Enter users file path: users_small.txt

------------------------------------------------------------------------

## 🖥️ Application Menu

    1. Add Friend
    2. Remove Friend
    3. Display Friend List (Sorted)
    4. Display nth Level Friends
    5. Display Countries in Network
    6. Log Out
    7. Display Menu

------------------------------------------------------------------------

## 🔑 Error Handling

The program uses error codes for handling failures such as: - Duplicate
users - Authentication failure - Friend not found - User not found

------------------------------------------------------------------------

## 📚 Learning Outcomes

This project demonstrates: - Building structured applications -
Designing authentication logic - Implementing graph traversal
algorithms - Working with real-world data relationships

------------------------------------------------------------------------

## 📌 Notes

-   This project was completed individually.
-   No external libraries were used beyond Python standard library.
-   Dataset used does not belong to the collaborator
-   It was provide by Penn State University for academic coursework.
-   Used only for educational purposes.

------------------------------------------------------------------------

## 🛠 Future Improvements

-   GUI or Web Interface (Flask / React)
-   Stronger encryption method (Hashing)
-   Database storage instead of file input
-   Unit testing support
