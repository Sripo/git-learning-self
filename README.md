# Git and Maven Learning Guide for Beginners

Welcome to the Git and Maven learning guide! This guide is designed to help junior and newly joined developers learn how to use Git for version control and Maven as a build tool. Each step is explained in simple terms to make it easy to follow along.

## Introduction

### What is Git?
- **Git** i is a distributed version control system used to track changes in your code. It allows you to push (upload) and pull (download) your code to and from a central repository (like GitHub or Bitbucket).
- Git helps multiple people work on the same project without overwriting each other's work.

### What is Maven?
- **Maven** is a tool that builds and manages Java projects.
- It compiles your code, manages libraries (dependencies) your project needs, and packages the code into files like `.jar` or `.war` that can be used in your application.

### Key Differences Between Git and Maven
- **Git**: Think of Git as the storage space for your code.
- **Maven**: Think of Maven as the tool that makes sure your code is correctly compiled and ready to run.

## Getting Started(Onboarding): Cloning and Building the Project

Follow these steps when you first start working with the project. To start working with a project using Git and Maven:

### Step 1: Setting Up Your Workspace
1. **Create a Workspace Folder**:
   - On your local computer, create a new folder called `Workspace`.
2. **Create a Project Folder/Version Folder**:
   - Inside the `Workspace` folder, create another folder with the name of your project or the project version.
3. **Open Git Bash**:
   - Right-click inside the project folder and select `Git Bash Here` to open the Git terminal.

### Step 2: Cloning the Repository
4. **Clone the Repository**:
   - Run the following command in the Git Bash terminal:
     ```bash
     git clone <repository_URL>
     ```
   - This command will download the project files from the repository to your local computer.

### Step 3: Open the Project in Your IDE
5. **Open the Project in Your IDE**:
   - Open your Integrated Development Environment (IDE) like IntelliJ or Eclipse.
   - Go to `File` > `Open` and select the project folder you cloned in the previous step.

## Basic Git Commands Explained

### Common Git Commands You Should Know
- **Clone a Repository**: This command creates a copy of the project on your computer.
  ```bash
  git clone <repository_URL>
  ```
- **Update your local Code**: This command fetches the latest changes from the repository to make sure your code is up-to-date.
  ```bash
  git pull
  ```  
- **Create a New Branch**: This creates a new branch to work on without affecting the main code.
  ```bash
  git checkout -b <branch_name>
  ```
- **Stage Changes to your Code**:
