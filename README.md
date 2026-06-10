# KTU Android Mobile Application Development Project

## Overview

This repository serves as the foundation for a semester-long Android Mobile Application Development project. Students will use Java and Android Studio to design, build, test and enhance a mobile application through multiple assignment phases.

Rather than creating a new repository for each assignment, students will continuously develop the same application throughout the semester. This approach enables proper version control, demonstrates project evolution, and allows lecturers to review each student's development process using GitHub.

---

## Learning Objectives

By participating in this project, students will learn how to:

* Develop Android applications using Java and Android Studio.
* Apply object-oriented programming concepts in mobile development.
* Use Git and GitHub for version control.
* Manage software development through incremental improvements.
* Document software projects professionally.
* Track application changes through commits, branches, and releases.
* Collaborate using industry-standard development workflows.

---

## Repository Structure

```text
ktu-android-mobile-app-project/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│
├── gradle/
├── screenshots/
│   └── Screenshot_IndexNumber.png
│
├── README.md
├── build.gradle
├── settings.gradle
├── gradlew
└── gradlew.bat
```

---

## Assignment Workflow

Each assignment will build upon the previous version of your application.

Example:

### Assignment 1

* Create project structure.
* Design an android app.
* Implement basic navigation including a linear and horizontal layout that can scroll

Students must continue developing the same project throughout the semester.

---

## Student Participation Guide

### Step 1: Fork the Repository

Click the **Fork** button on GitHub to create your own copy of this repository.

Example:

```text
Original Repository:
ktu-android-mobile-app-project

Your Fork:
your-github-username/ktu-android-mobile-app-project
```

---

### Step 2: Clone Your Fork

Clone your fork to your local machine.

```bash
git clone https://github.com/your-username/ktu-android-mobile-app-project.git
```

---

### Step 3: Open in Android Studio

1. Launch Android Studio.
2. Select **Open Project**.
3. Choose the cloned repository folder.
4. Allow Gradle to synchronize.

---

### Step 4: Develop Your Application

Implement the assignment requirements within the project.

Students are encouraged to:

* Commit regularly.
* Write meaningful commit messages.
* Test their application before pushing changes.

Example:

```bash
git add .
git commit -m "Added user registration screen"
git push origin main
```

---

### Step 5: Document Your Work

Update the README with:

* Student Name
* Student ID
* Application Name
* Assignment Progress
* Features Implemented
* Screenshots

---

## Submission Requirements

Each student repository must contain:

### Source Code

All Android Studio source files required to build and run the application.

### Screenshot Folder

```text
screenshots/
```

Include at least:

```text
Screenshot_B202230014.png
```

The screenshot must clearly show the application's main screen.

Additional screenshots may be added to demonstrate implemented features.

---

### Project Documentation

Update this README to include:

#### Student Information

```text
Name: John Doe
Student ID: B202230014
Course: Mobile Application Development
```

#### Application Information

```text
Application Name: Smart Expense Tracker
```



## Assignment Milestones

Students should create Git tags after completing each assignment.

Example:

```bash
git tag assignment-1
git push origin assignment-1
```

```bash
git tag assignment-2
git push origin assignment-2
```

```bash
git tag assignment-3
git push origin assignment-3
```

This allows lecturers to review the project at specific submission points.

---

## Git Commit Guidelines

Use descriptive commit messages.

Good Examples:

```text
Added login activity
Implemented SQLite database
Designed home screen UI
Added navigation drawer
Fixed input validation bug
```

Avoid:

```text
Update
Changes
Work done
Final
```

---

## Files That Must Not Be Committed

The following generated files should not be uploaded:

```text
.gradle/
build/
app/build/
.idea/
local.properties
captures/
.externalNativeBuild/
.cxx/
```

Ensure the provided `.gitignore` file remains unchanged.

---

## Academic Integrity

Students must:

* Develop their own work.
* Avoid copying source code from classmates.
* Maintain an authentic commit history.

Repositories found to contain plagiarized work may be subject to academic penalties.

---

## Support

If you encounter technical issues:

1. Review Android Studio build logs.
2. Verify Gradle synchronization completed successfully.
3. Check repository issues and announcements.
4. Contact the course instructor or teaching assistant.

