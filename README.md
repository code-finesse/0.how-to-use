# How To Contribute
This is a step by step guide on how to contribute to the repositories in this github organization.

## Fork the repository


Fork the repository by clicking on the fork button on the top of the page. This will create a copy of this repository in your account.

***If it's a new topic you can also clone down the [repo-template](https://github.com/code-finesse/repo-template) to start from scratch***

## Clone the repository

[![clone this repository](https://camo.githubusercontent.com/4c3f7f1bec4f04db40ecf58dc2e19c2d8992f100f3bbbc4767a9d20b29f4a43d/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f526561646d652f636c6f6e652e706e67)](https://camo.githubusercontent.com/4c3f7f1bec4f04db40ecf58dc2e19c2d8992f100f3bbbc4767a9d20b29f4a43d/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f526561646d652f636c6f6e652e706e67)

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the  _copy to clipboard_  icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"

```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

[![copy URL to clipboard](https://camo.githubusercontent.com/1c0cf8056422ff414eee75142b213c5970e085c2e33c0a6d69dc2639d98216f1/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f526561646d652f636f70792d746f2d636c6970626f6172642e706e67)](https://camo.githubusercontent.com/1c0cf8056422ff414eee75142b213c5970e085c2e33c0a6d69dc2639d98216f1/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f526561646d652f636f70792d746f2d636c6970626f6172642e706e67)

For example:

```
git clone https://github.com/this-is-you/code-finesse.git

```

where  `this-is-you`  is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd code-finesse

```

Now create a branch using the  `git checkout`  command:

```
git checkout -b your-new-branch-name

```

For example:

```
git checkout -b add-cool-contributor

```

(The name of the branch does not need to have the word  _add_  in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes


Now add and commit those changes:
```
git add .

```

```
git commit -m "Add <your-name> to Contributors list"

```

replacing  `<your-name>`  with your name.

## Push changes to GitHub

Push your changes using the command  `git push`:

```
git push origin <add-your-branch-name>

```

replacing  `<add-your-branch-name>`  with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request`  button. Click on that button.

[![create a pull request](https://camo.githubusercontent.com/ca3b1cefece5f3b9b3435020e6a357ca024cda5bd2b1e140a15170fcd1ec5381/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f526561646d652f636f6d706172652d616e642d70756c6c2e706e67)](https://camo.githubusercontent.com/ca3b1cefece5f3b9b3435020e6a357ca024cda5bd2b1e140a15170fcd1ec5381/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f526561646d652f636f6d706172652d616e642d70756c6c2e706e67)

Now submit the pull request.

[![submit pull request](https://camo.githubusercontent.com/71401ba5551a64aeac3838825a52ce7a7597cd8b54a0d7200d9454e2cbfbb13f/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f526561646d652f7375626d69742d70756c6c2d726571756573742e706e67)](https://camo.githubusercontent.com/71401ba5551a64aeac3838825a52ce7a7597cd8b54a0d7200d9454e2cbfbb13f/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f526561646d652f7375626d69742d70756c6c2d726571756573742e706e67)

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard  _fork -> clone -> edit -> pull request_  workflow that you'll encounter often as a contributor!

You could join our discord in case you need any help or have any questions.  [Code Finesse Discord](https://discord.gg/TTJJrnhAsG).
