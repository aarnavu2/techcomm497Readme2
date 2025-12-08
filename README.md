<p align="center">
  <img src="https://github.com/aarnavu2/techcomm497Readme2/blob/main/Screenshot%202025-12-08%20092644.png" alt="Project Banner">
</p>

# ReadMe for Habit Tracker App  

## Table of Contents  
- [About the Project](#about-the-project)  
- [Quickstart Guide](#quickstart-guide)  
- [Features](#features)  
- [Architecture](#architecture)  
- [Usage Examples](#usage)  
- [FAQ](#faq)  

---

## About the Project  
HabitHero is a Flutter-based mobile app designed to help users create, track, and maintain healthy habits.  

- **Audience:** Individuals between the ages of 18 and 30 who want to build better habits.  
- **Purpose:** Staying consistent is challenging but the Habit Tracker incentivizes good habits through gamifying good habits.

---

## 🚀 Quickstart Guide  

### Installation  
1. Clone the repo:  

   ```bash
    git clone git@github.com:aarnavu2/497Project.git
    cd 497Project
    ```

2. Install dependencies:
    ```bash
    flutter pub get
    ```

3. Run the app:
    ```bash
    flutter run
    ```


## Features
- **Home Page**
- **Friends Page**
- **Current Habits Page**
- **Challenges Page**

## Architecture
<img src="https://github.com/aarnavu2/techcomm497Readme2/blob/main/Architecture%20Diagram.png" alt="Architecture" width="300" />

## Usage

Adding a habit demo  
<img src="https://github.com/aarnavu2/techcomm497Readme2/blob/main/addHabitGif.gif" alt="Usage1 Gif" width="600" />

Adding a streak to an already created habit  
<img src="https://github.com/aarnavu2/techcomm497Readme2/blob/main/addStreakGif.gif" alt="Usage 2 Gif" width="600" />

This is the home page which allows the user to navigate to different portions of the website.  
<img src="https://github.com/aarnavu2/techcomm497Readme2/blob/main/homepage.png" alt="Home Page" width="600" />

If the user clicks on create new habit, they get taken to this page where they can select the category of habit they are interested in.  
<img src="https://github.com/aarnavu2/techcomm497Readme2/blob/main/create_new_habit.png" alt="Create Habit Page" width="600" />

Once the user clicks view habits on the previous page, they can select the specific habits from the category they picked.  
<img src="https://github.com/aarnavu2/techcomm497Readme2/blob/main/select_habit.png" alt="See Habit Page" width="600" />

If they click on the friends page they get taken here to see their friends.  
<img src="https://github.com/aarnavu2/techcomm497Readme2/blob/main/view_friends.png" alt="Friends Page" width="600" />

If they want to see their streak they can click on the streaks page  
<img src="https://github.com/aarnavu2/techcomm497Readme2/blob/main/view_streaks.png" alt="Streaks Page" width="600" />

They can also update their streaks using our streak updating feature  
<img src="https://github.com/aarnavu2/techcomm497Readme2/blob/main/add_streak.png" alt="Update Streaks Page" width="600" />

## FAQ
**Q: Do I need an account to use Habit Tracker?**
A: No, Habit Tracker relies on Flutters internal data structures to store data locally

**Q: Can I reset a habit’s streak?**
A: Yes, streaks can be reset from the Current Streaks page.

**Q: Is there support for syncing across devices?**
A: Not yet—currently, all data lives locally. Future versions may integrate cloud storage.

**Q: How do I add a streak**
A: Go to the habits page, select new habit, and then go to current streaks and add 1 to your streak
