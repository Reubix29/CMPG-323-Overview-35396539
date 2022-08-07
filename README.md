# CMPG-323-Overview-35396539
This is a repo for the implementation of the Agile and Scrum frameworks for the CMPG 323 module

The module consists of five projects (including this one) and a Portfolio of Evidence. The URLs of the other projects are as follows:
Project 2 (API Development): https://github.com/Reubix29/CMPG-323-Project-2---35396539.git
Project 3 (Standards & Patterns): https://github.com/Reubix29/CMPG-323-Project-3---35396539.git
Project 4 (Testing & RPA): https://github.com/Reubix29/CMPG-323-Project-4---35396539.git
Project 5 (Reporting & Monitoring): https://github.com/Reubix29/CMPG-323-Project-5---35396539.git

The module progress is linked to a GitHub project: https://github.com/users/Reubix29/projects/1/views/2

This is how the Repositories and project tie in together:

![Alt text](/Repositories.png?raw=true "Repository Context Diagram")

Each project will use two branches: main (the current working program), and dev (where development will take place). When development on a dev branch has reached a stability, e.g. when a feature has been added and tested, it will be merged with the main branch.

When committing changes, the following keywords are to be used: feat, fix, change.
feat = new features
fix = bug fixes
change = adding or deleting a file

e.g.

feat(filename): short description of what exactly was changed.

The gitignore file is used to indicate which files should be ignored when committing and pushing changes. Files that will be listed here are any files that contain sensitive data (e.g. API keys), or system specific files.

Credentials and sensitive information will be stored in separate files and included in the gitignore file instead of hard coded in, which will ensure security, as it will not be accessible from the repository itself.