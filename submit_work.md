# Submit Work

###### tags: `webaverse`

After you have tested the project, reported any bugs, and created a README, you can submit your work for the bounty. There are a couple ways you can submit the finished README:

1. (Beginners) Submit work to Dework by drag n' dropping the README.md file into the file drop area

> Note: It's recommended to link the README you made as a fresh HackMD note in the GitHub issue for quick feedback, though this step is optional. 

![](https://i.imgur.com/N7An0Ob.png)

2. (Advanced) Create a new branch in the webaverse-mmo repo with your changes, then make a pull request to the main branch

If you're new to git, this flow looks something like this: you clone the `webaverse-mmo` repo, make some changes (like creating / modifying the README.md file) and save them to a new branch, then it gets merged back in later with approval from the maintainer through a pull request.

![](https://i.imgur.com/4vZHXiv.png)

The command line version of these steps looks like this:

```bash
# Clone the repo and enter it
$ git clone git@github.com:webaverse-mmo/meta.git
$ cd meta/
# Edit and save the README file
$ vim README.md
# Change to a new branch
$ git checkout -b readme
# Add and commit the file to new branch
$ git add README.md
$ git commit -m "add readme"
# Push changes to the readme branch
$ git push -u origin readme
```

You'll then see a new message show up on the `webaverse-mmo` project's page, like so:

![](https://i.imgur.com/bvkI4OP.png)

Go ahead and click the button to compare and make a pull request, and verify that it's to merge your branch with the main one. If you're satisfied with your changes and ready to submit your work you may do so this way.
