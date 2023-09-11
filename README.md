## Table of contents

- [Questions](#Questions)
  - [how to remove them locally and remotely?](#how-to-remove-them-locally-and-remotely?)
  - [how to checkout another branch without commit changes?](#how-to-checkout-another-branch-without-commit-changes?)
  - [how to list tags?](#how-to-list-tags?)
  - [how to delete tag locally and remotely?](#how-to-delete-tag-locally-and-remotely?)
  - [Screenshot](#screenshot)

## Questions

### how to remove them locally and remotely?

Removing Branches Locally:
git branch -d dev  
git branch -d test

Removing Branches Remotely:
git push origin --delete dev  
git push origin --delete test

### how to checkout another branch without commit changes?

by using git stash then git checkout new-branch-name

### how to list tags?

git tag

### how to delete tag locally and remotely?

Deleting a Tag Locally:
git tag -d tag_name

Deleting a Tag Remotely:
git push origin --delete tag_name

### Screenshot

![index page](index-page.PNG)
