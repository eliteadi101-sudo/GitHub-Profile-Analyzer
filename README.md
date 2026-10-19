# GitHub Profile Analyzer

Look up a public GitHub username and summarize repositories, stars, and language usage.

## Tech stack
HTML, CSS, JavaScript, GitHub REST API

## Features
- A working core implementation with a simple, usable interface or CLI.
- Input validation and basic error handling where appropriate.
- Source code organized for learning and extension.

## Getting started

Choose the instructions for this project's stack.

1. Install JDK 17+ and Maven.
2. Run from this directory:
   ```bash
   mvn package
   mvn exec:java -Dexec.mainClass=dev.student.LibraryApp
   ```
   If the Maven exec plugin is not configured in your environment, compile and run with your IDE, or use:
   ```bash
   javac -d out src/main/java/dev/student/LibraryApp.java
   java -cp out dev.student.LibraryApp
   ```

## Project structure

The source files are kept in the root directory or in `public/`, `templates/`, or the conventional language-specific folders. Generated local databases, secrets, and dependency folders are excluded with `.gitignore` where applicable.

## Notes
- These are intermediate-level starter repositories intended for learning and customization. Review, test, and personalize them before presenting them as your own work.
- Never commit API keys, passwords, tokens, or private user data.
- Some projects use external APIs and therefore require an internet connection.
