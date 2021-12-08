# How can I contribute?

Open an [Issue](https://github.com/lucalves/ios-learning-resources/issues/new) with the links you want to share, I will add it when possible. If you'd like to create a Pull Request, please follow the instructions below.

# Fork & create a branch

With the Issue created, fork ios-learning-resources and create a branch with the issue number.

A good branch name would be (example):

```git checkout -b feature/my-new-resource```

# Make a Pull Request

At this point, you should switch back to your main branch and make sure it's up to date with ios-learning-resources branch:

```
git remote add upstream git@github.com:lucalves/ios-learning-resources.git
git checkout main
git pull upstream main
```

Them update your feature branch from your local copy of main, and push it!

```
git checkout feature/my-new-resource
git rebase main
git push --set-upstream origin feature/my-new-resource
```

Finally, go to GitHub and make a [Pull Request](https://github.com/lucalves/ios-learning-resources/pulls) 😄
