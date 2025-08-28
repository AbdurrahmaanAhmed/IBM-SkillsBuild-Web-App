# About
This project is a gamified web application for IBM SkillsBuild, developed as part of the CO2302 Software Engineering Group Project at the University of Leicester in collaboration with IBM.

The platform aims to encourage student engagement with IBM SkillsBuild learning resources through gamification. By integrating features such as leaderboards, progress tracking, and badges, the app transforms the learning experience into an interactive journey.

🌟 Core Features

    User Authentication – Secure login for students.

    SkillsBuild Integration (Simulated) – Access IBM SkillsBuild courses and track progress.

    Progress History – View a record of completed courses.

    Gamification – Earn badges and achievements as you progress.

    Leaderboards – Compete globally or with friends to motivate continued learning.

🎯 Project Goal
The system encourages students to actively use IBM SkillsBuild, helping them gain digital credentials and showcase their skills for future careers, while providing a fun and engaging user experience.


⚙️ Setup

🗄️ Setting Up MySQL

    Open MySQL and log in as the root user.

    Create a new database schema named skillsyncdb:

    CREATE DATABASE skillsyncdb;

    In MySQL Workbench, go to Administration > Users and Privileges.

    Create a new user with the following credentials:

        Username: skillsync

        Password: 123456789

    Assign the Administration role and grant all privileges to this user.

    Ensure the MySQL service is running before starting the application.

💻 Setting Up in IntelliJ

    Open IntelliJ IDEA and navigate to the Database tab.

    Click Add Database.

    Select MySQL as the database type.

    Enter the following credentials:

        User: skillsync

        Password: 123456789

        Database Name: skillsyncdb

    Click Test Connection to verify the setup.

    Once successful, click Apply to save the configuration.
