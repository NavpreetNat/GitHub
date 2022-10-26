# Using the branches function in GitHub
*Below are commands used for pushing and pulling from your own branch on GitHub*

---

1. Always make sure to 'pull' from the main repo to ensure that you have the most up-to-date files. First, make sure that the branch that you're in in Git Bash/terminal is the (main) branch for 'Crypto_Master'. Then, use the pull command:

```shell
git pull
```

---

2. After working on the files on your local computer, once you're ready to push the files to your own branch on the remote repo, make sure to first navigate into your branch in Git Bash/terminal using:

```shell
git checkout firstname_lastname
```

---

3. You can double check that you're in the correct branch as it will say (firstname_lastname) in Git Bash/terminal. Conversely, you can also use this command:

```shell
git branch
```

*The terminal will then display which branch you're in by an asterix* (*) *besides the branch name in the terminal*

---

4. Once you have confirmed that you are in the correct branch, use the following command to push your updates to your unique branch:

```shell
git push origin firstname_lastname
```

---

5. If at any time you wish to navigate back to main, use this command:

```shell
git checkout main
```

You can then also confirm this with ``` git branch``` to double check where you are, for good measure.