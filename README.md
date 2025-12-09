# 🎵 Java Playlist Manager
A Fully Functional Music Playlist System Built Using Custom Singly and Doubly Linked Lists

Welcome to the Java Playlist Manager — a hands-on data structure project designed to help you understand how linked lists work by building something fun, practical, and interactive: a music playlist!

This project goes beyond static examples and textbooks. It simulates how real music apps manage playlists internally, including navigating through songs, preventing duplicates, and maintaining forward/backward traversal using custom Node classes — without relying on Java’s built-in collections.

🚀 Project Overview

This application implements a complete playlist management system using both:

Singly Linked List

Doubly Linked List

It demonstrates how data structures work behind the scenes by manually managing:

Node creation

Pointer connections (next and previous)

Insertions at the beginning/end

Middle-node removal

Sequential forward/backward navigation

You'll get a deep understanding of how real-world playlists (like Spotify, Apple Music, etc.) might maintain song order internally.

🎯 Key Features
✔️ Add Songs to the Playlist

Prevents adding duplicate songs

Automatically adjusts head/tail pointers

Supports adding at the beginning or end of the list

✔️ Remove Songs

Handles all removal cases:

Removing the first song (updating head)

Removing the last song (updating tail)

Removing middle songs

✔️ Navigate Through Songs

playNextSong()
Moves to the next node and prints the currently playing song.

playPreviousFavoriteSong()
(Doubly linked version) Moves backward using the previous pointer.

✔️ Check for Duplicate Songs

Ensures the playlist only contains unique entries.

✔️ Print Full Playlist

Displays all songs from start to end, exactly as you would see in a music player.

🧠 What You Will Learn

This project is designed to reinforce core computer science concepts:

🔹 Data Structures

How linked lists are built from scratch

How pointers connect nodes

How to manage head/current/tail references

🔹 Algorithmic Thinking

Searching for items in O(n) time

Handling pointer updates safely

Decision-making for corner cases

🔹 Object-Oriented Programming

Custom Node classes

Composition (Song inside Node)

Encapsulation and modular design

🛠️ Technologies Used
Component	Purpose
Java	Main programming language
Custom Singly Linked List	Forward-only playlist navigation
Custom Doubly Linked List	Forward and backward playlist navigation
Song Class	Represents song metadata
Node Class	Building block of both linked lists
📂 Project Structure
src/
 ├── Song.java
 ├── SinglyLinkedPlaylistManager.java
 ├── DoublyLinkedPlaylistManager.java
 ├── Main.java


Each playlist manager contains:

Inner Node class

Head pointer

Current pointer

Add/remove/search methods

Navigation methods

🧪 Sample Functions
Adding a Song
addSong(new Song("Shape of You"));

Playing Next Song
playNextSong();

Removing Current Song
removeCurrentSong();

🌟 Why This Project Matters

Linked lists are one of the most important fundamental data structures, yet they are often misunderstood because developers don’t get hands-on practice building them.

This project fixes that.

By building a playlist manager with real functionality, you learn:

Why linked lists exist

Where they outperform arrays

How to maintain them safely

What happens when pointers break

How modern apps structure data internally

If you are preparing for programming interviews, university assignments, or simply want to become a stronger Java developer — this project is perfect for your portfolio.

💬 Contribute / Fork

Feel free to fork the project, add your own features, or optimize the code.
Some suggested extensions:

Shuffle mode

Repeat mode

Search by artist/song name

Load playlist from a file

Save playlist to JSON

📣 Final Notes

This project is intentionally designed to be educational, clean, and beginner-friendly, making it ideal for:

Students

Self-learners

Junior developers

Anyone revising for coding interviews

If you're learning Java and want to truly understand linked lists instead of just reading about them — this project will take your skills to the next level.
