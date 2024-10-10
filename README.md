# Git and Maven Learning Guide for Beginners

## Introduction

### What is Git?
Git is a distributed version control system used to track changes in your code. It allows you to push (upload) and pull (download) your code to and from a central repository (like GitHub or Bitbucket).

### What is Maven?
Maven is a build automation tool used primarily for Java projects. It helps in building the project, managing dependencies, and packaging the code into deployable formats like `.war` and `.jar` files.

### Key Difference
- **Git**: Think of it as the storage or central repository for your code.
- **Maven**: Think of it as the tool that compiles your code and ensures your application runs properly by handling dependencies.

## Onboarding: Cloning and Building the Project

Follow these steps when you first start working with the project:

### Step 1: Set Up Your Workspace
1. **Create a Workspace Folder**: Create a folder named `Workspace` on your local machine.
2. **Create a Version Folder**: Inside the `Workspace` folder, create another folder with the project version or release name.
3. **Open Git Bash**: Right-click in the version folder and select `Git Bash Here`.

### Step 2: Clone the Repository
4. Run the command: This will copy the project repository to your local machine.
   ```bash
   git clone <repository_URL>
   ```
   
