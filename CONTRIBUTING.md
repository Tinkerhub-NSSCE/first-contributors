# How can you contribute?

To know about hacktoberfest [click here](https://hacktoberfest.com/)

## Requirements

- [A GitHub Account](https://GitHub.com)
- [Git installed in your system](https://docs.GitHub.com/en/get-started/quickstart/set-up-git)
- [Hacktoberfest Account](https://hacktoberfest.com)

**Note:** If you want to be a part of hackctoberfest [complete registration and authorization](https://hacktoberfest.com/register/) before your pull request.

---

## Step 1 - Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Step 2 - Clone the forked repository

Now clone the forked repository to your machine:

- Using HTTPS

```sh
git clone "https://github.com/<your-username>/first-contributors"
```

- Using SSH

```sh
git clone "git@github.com:<your-username>/first-contributors.git"
```

**Note**: Replace <yout-username> with your GitHub username.

> access and write data in repositories on GitHub.com using SSH (Secure Shell Protocol). When you connect via SSH, you authenticate using a private key file on your local machine.

[Generate a SSH Key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

## Step 3 - Create a branch

Change the current working directory to the cloned repo.
For example:

```sh
cd first-contributors
```

Now create a new branch with the below naming convention:

```sh
git switch -c add-your-name
```

For example:

```sh
git switch -c chaitanya-liz
```

## Step 4 - Make changes and commit

Now if you go to the project directory and enter the command `git status`, you can see the changes.

Add those changes with the `git add` command:

```sh
git add -A
```

Now commit those changes using the `git commit` command:

```sh
git commit -m "Add <your-name> to contributors list"
```

For example:

```sh
git commit -m "Add chaitanya-liz to contributors list"
```

## Step 5 - Push the changes to GitHub

Push your changes to GitHub using the `git push` command:

```sh
git push -u origin <your-branch-name>
```

For example:

```sh
git push -u origin chaitanya-liz
```

## Step 6 - Submit your changes for review

If you go to your repository page on GitHub you will see a `compare & pull request` button. Click that button.
And submit the pull request.
Soon the reviewer will merge the branch into `main`.
