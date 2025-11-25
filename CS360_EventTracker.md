# CS-360 Event Tracker — Android App Artifact (Software Design & Engineering)

## Overview
The Event Tracker application was originally created in **CS-360: Mobile Architecture and Programming**.  
It allowed users to create and manage simple event entries inside a basic Android interface.

For my **CS-499 Computer Science Capstone**, I selected this project as my **Software Design & Engineering artifact** because it clearly demonstrates how I can transform an academic prototype into a professionally structured, maintainable application.  
I enhanced the original project and then produced a final version containing ample comments for clarity and long-term maintainability.

---

# 📌 Original Artifact (Before Enhancement)

### Summary of the Original CS-360 Version
The original app was built using early Android development principles:

- Logic was handled mostly inside Activities  
- Limited separation of concerns  
- Basic UI with simple input fields  
- No architectural layers (no MVVM, Repository, or Room)  
- Minimal documentation and comments  
- Events were stored using simple or temporary approaches  

This version worked functionally but was not yet designed for scalability or maintainability.

### Download — Original Version  
📦 **Original CS-360 EventTracker Project**  
➡ **[Download CS360_Event_TrackerStarter_Before.zip](CS360_Event_TrackerStarter_Before.zip)**

---

# 📌 Final Enhanced Artifact — CS-499 Submission

### Summary of Improvements
For CS-499, I redesigned the project to align with professional Android development standards:

### ✔ Introduced MVVM Architecture  
- Separated UI logic from data and business logic  
- Added a clean ViewModel layer  
- Improved maintainability and testability  

### ✔ Added Room Database for Persistent Storage  
- Created `Event`, `EventDao`, and `EventDatabase`  
- Enabled local on-device data persistence  
- Removed the need for temporary in-memory storage  

### ✔ Added Repository Layer  
- Centralized data operations  
- Improved scalability and consistency  
- Prepared the codebase for future enhancements (e.g., API sync)  

### ✔ Improved UI/UX  
- Added RecyclerView with a custom EventAdapter  
- Organized event items in card layouts  
- Added validation and stable user interactions  

### ✔ Added WorkManager Scaffold  
- Introduced background processing structure  
- Demonstrates industry-standard practices  

### ✔ Added Ample Comments  
- File-level headers describing each class  
- Method-level Javadoc-style explanations  
- Improved readability and clarity for reviewers  

This version is the **official** CS-499 artifact submission.

### Download — Enhanced + Commented Version  
📦 **Final Enhanced Artifact (With Ample Comments)**  
➡ **[Download EventTracker_Enhanced_CS499_commented.zip](EventTracker_Enhanced_CS499_commented.zip)**

---

# 🎓 CS-499 Outcomes Demonstrated

### **Outcome 1 — Design and Evaluate Computing Solutions**
Redesigned the app using MVVM, Repository, and Room to evaluate and produce a scalable, maintainable solution.

### **Outcome 2 — Professional Communication**
Added comprehensive comments and clear documentation to communicate design intent and improve readability.

### **Outcome 4 — Use Appropriate Tools and Techniques**
Applied Android frameworks (Room, LiveData, ViewModel, WorkManager, RecyclerView) to deliver a professional-grade application.

---

# 🧠 Reflection
Transforming this CS-360 project into a CS-499 artifact helped me understand how proper architecture directly impacts maintainability, reliability, and scalability.  
The enhanced version resembles a real-world Android application and reflects my growth from student-level coding to professional software engineering practices.

---

[⬅ Back to Home](index.html)
