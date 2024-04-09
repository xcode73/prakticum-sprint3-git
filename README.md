# Xcode Git Integration Guide

This guide provides step-by-step instructions for integrating Git with Xcode. It covers creating a local repository for a new project, adding a local repository to an existing project, and creating a repository on GitHub directly from Xcode.

## Creating a Local Repository for a New Project

1. Open Xcode and select "Create a new Xcode project".
2. Ensure that "Create Git repository on my Mac" is checked. Click "Create".

<img width="416" alt="Screenshot 2024-04-09 at 13 19 25" src="https://github.com/xcode73/prakticum-sprint3-git/assets/11060275/107663be-661c-4948-9daa-e607ec4c262f">

*Xcode will automatically initialize a local Git repository for your new project.*

## Adding a Local Repository to an Existing Project

1. Open your existing Xcode project.
2. Go to Integrate > New Git Repositories….

<img width="341" alt="Screenshot 2024-04-09 at 13 21 33" src="https://github.com/xcode73/prakticum-sprint3-git/assets/11060275/e27f91bb-b953-4b20-8c78-ad817777aed9">

*Xcode will initialize a local Git repository for your existing project.*

<img width="333" alt="Screenshot 2024-04-09 at 13 22 23" src="https://github.com/xcode73/prakticum-sprint3-git/assets/11060275/7cea0c37-9501-4332-9f9f-f7dd72f20112">

## Creating a Repository on GitHub from Xcode

1. Open your Xcode project.
2. Go to Source Control > Right click on Remotes
   
<img width="341" alt="Screenshot 2024-04-09 at 13 22 49" src="https://github.com/xcode73/prakticum-sprint3-git/assets/11060275/1b1989bc-eabc-480e-887e-a922b80c096e">

<img width="561" alt="Screenshot 2024-04-09 at 13 23 14" src="https://github.com/xcode73/prakticum-sprint3-git/assets/11060275/04e2b563-d154-40ac-b439-297870b115ba">

*Xcode will push your project to the GitHub repository, creating it if it doesn't exist already.*

<img width="676" alt="Screenshot 2024-04-09 at 13 25 09" src="https://github.com/xcode73/prakticum-sprint3-git/assets/11060275/8d6d52d5-5cc0-4321-936c-badcdbff53e2">

## Additional Notes

**Branch Management:** You can create and switch between branches using the Source Control navigator in Xcode.
**Committing Changes:** Use the Source Control navigator or the Source Control menu to commit changes to your local repository.
**Pulling Changes:** Use the Source Control navigator or the Source Control menu to pull changes from the remote repository.
**Resolving Conflicts:** Xcode provides tools to help you resolve merge conflicts within the IDE.
By following these steps, you can effectively manage your Xcode projects using Git, both locally and remotely on GitHub.
