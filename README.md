# Bookstore Template

## Content
- [Deployed Site](#deployed-site)
- [Interface](#interface)
- [Steps to contribute](#steps-to-contribute)
- [Commit Guidelines](#commit-guidelines)
- [Points to Consider while Contributing](#points-to-consider-while-contributing)

## Deployed Site
[Test Deployment](https://sanket-mathur.github.io/Bookstore-template/)

## Interface
![Screenshot of Deployed Site](Display/Landing.png)

## Steps to contribute
![HacktoberFest 2021](https://hacktoberfest.digitalocean.com/_nuxt/img/logo-hacktoberfest-full2.aa1e9d9.svg)
In order to contribute to this project, follow the steps below:
- Fork the project, using the gray `Fork` button in the top right of this page
- Clone your forked repository
  ```bash
  git clone https://github.com/<Username>/Bookstore-template.git
  ```
- Create a branch in your local repository to make your changes in
  ```git
  git checkout -b your-branch
  ```
- After making changes in your local repository, add the files changed
  ```git
  git add file-name
  ```
- Commit changes when you are satisfied. Refer to [Commit Guidelines](#commit-guidelines)
  ```git
  git commit -am "<message>"
  ```
- Push changes to your remote forked repository
  ```git
  git push -u origin your-branch
  ```
- Go back to your repository and submit a Pull Request with the commits you want to merge with the project
- Follow up with the comments in your pull requests until it is merged

## Commit guidelines
Use the following commit category at the beginning of your message, to make commits easy to follow:
- **feat** - for new features
- **fix** - for defects or bugs
- **chore** - for changes that don't alter the source, but necessary
- **ci** - for ci pipeline changes
- **docs** - for documentation changes
- **perf** - for performance enhancements
- **refactor** - for refactors; altering the code, but not changing functionality
- **revert** - reverting changes
- **style** - for cosmetic changes
- **test** - for unit tests

## Points to consider while contributing
- Use generalized design patterns
- Try to use CSS variables for commonly used values
- Do not repeat already existing code
- Do not add any unnecessary comments in between the code
- Maintain original code formatting to avoid merge conflicts
