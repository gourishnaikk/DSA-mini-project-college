# DSA-mini-project-college
# 🎵 BeatLinked-Smart Music Playlist Management System

A **Java console-based mini project** that uses **core Data Structures (Linked List, Queue, and Stack)** to manage and predict songs intelligently based on user interactions.  
This project demonstrates the application of **DSA concepts** in building a lightweight, automated music management system.

---

## 📘 Introduction

The **Predictive Song Playlist System** is designed to simulate a simple yet smart music player that can:
- Add and play songs
- Keep track of recently played tracks using a **Queue**
- Undo the last action using a **Stack**
- Predict the next song based on **listening patterns** (recency-based logic)

It combines fundamental DSA operations to create a system that behaves intelligently without relying on advanced algorithms or external data structures like HashMaps.

---

## 🧩 Problem Statement

To build a **music playlist manager** that utilizes **Linked List, Queue, and Stack** for efficient song management, playback history, and prediction of the next song.

---

## 🎯 Objectives

- Implement core DSA structures (LinkedList, Queue, Stack) in a real-world use case.  
- Automate song playback and prediction logic.  
- Provide efficient user operations like play, skip, and undo.  
- Demonstrate data handling and traversal techniques using custom DSA implementations.

---

## 🌐 Scope of the Project

- Demonstrates real-world applications of DSA in entertainment systems.  
- Can be extended to integrate APIs (like iTunes or Spotify).  
- Useful for students learning **Linked Lists and Queues** in a practical context.  
- Forms the base for building GUI-based or AI-integrated playlist systems.

---

## ⚙️ System Requirements

### **Hardware**
- Processor: Intel i3 or higher  
- RAM: 4 GB or more  
- Storage: 100 MB  

### **Software**
- **JDK 8 or higher (preferably JDK 17 or JDK 21)**  
- **VS Code / IntelliJ / Eclipse IDE**  
- **Java Console environment**

---

## 🧠 Data Structures & Concepts Used

| Data Structure | Purpose |
|----------------|----------|
| **Linked List** | To store and manage the song library |
| **Queue (FIFO)** | To maintain the recently played songs |
| **Stack (LIFO)** | To implement the undo functionality |
| **Prediction Logic** | Suggests the next song based on recent playback pattern |

---

## 🧮 Algorithm Explanation

1. **Add Song** → Insert new song object into the linked list.  
2. **Play Song** → Enqueue song into the “recently played” queue and push it into the undo stack.  
3. **Undo** → Pop the last song from the stack to revert the last action.  
4. **Prediction** → Analyze the recent queue to suggest the next likely song (e.g., repeat last played artist or next in sequence).  

---

## ⏱️ Time & Space Complexity

| Operation | Time Complexity | Space Complexity |
|------------|----------------|------------------|
| Add Song | O(1) | O(n) |
| Play Song | O(1) | O(n) |
| Undo | O(1) | O(n) |
| Predict | O(1) | O(n) |

---

## 💻 Implementation

The system runs in the **Java console** and provides a **menu-driven interface**:  
Add Song

Play Song

Undo Last Song

Show Recently Played Songs

Predict Next Song

Exit
