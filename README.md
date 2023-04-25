# new-project

## Setting up a Development Branch for New-Project

Welcome to the 'New-Project' GitHub repository! As a developer, you may need to work on new features or experiment with different approaches without affecting the main branch of the project. To do this, we recommend creating a development branch.

### Prerequisites

Before we begin, ensure that you have the following:

- A GitHub account
- Git installed on your local machine
- Access to the 'New-Project' repository
- Clone the repository to your local machine by running the following command:

```bash
git clone git@github.com:Searge/new-project.git

# Navigate to the cloned repository by running the following command:
cd new-project
```

### Working on the Development Branch

Creating a Development Branch

```bash
git checkout -b development
```

```bash
# To check out current branch, run the following command:
❯ git status
On branch development
...

```

To add changes to the staging area, run the following command:

```bash
git add .
```

To commit changes to the development branch, run the following command:

```bash
git commit -m "Add new feature"
```

To merge the development branch with the main branch, run the following command:

```bash
git checkout main
git merge development
```

To delete the development branch, run the following command:

```bash
git branch -d development
```

To push changes to the remote repository, run the following command:

```bash
git push origin main
```

## Conclusion

Creating a development branch is a useful way to work on new features or changes without affecting the main branch of the project. With these simple steps, you can easily create a development branch for the 'New-Project' repository and start working on new features. Happy coding!
