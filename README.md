### Create new project on local maching, then push it to remote repo
![image](https://github.com/menna-abdallah/VirsionControl_2/assets/139376864/71e42d89-a050-4063-8df9-3c111d23b70f)
![image](https://github.com/menna-abdallah/VirsionControl_2/assets/139376864/0e33a044-66c1-4600-8a3d-95440e3f89d1)

### Create two branches (dev & test), create one file on each branch, and push these changes to the remote repo.
![image](https://github.com/menna-abdallah/VirsionControl_2/assets/139376864/2f8712e7-2899-421e-a8a9-859be2699d29)

### Merge this changes on Master branch and then push it to your remote master branch.
![image](https://github.com/menna-abdallah/VirsionControl_2/assets/139376864/54af5ec6-ca9f-4e34-b374-27e3e4a4c5b1)

### How to remove branches locally and remotely

#### local:
#### git branch -d dev
#### git branch -d test
#### remote:
#### git push origin :dev
#### git push origin :test

### How to checkout another branch without commit changes?
#### You can use git stash to temporarily save your changes, switch to the other branch, and then apply the changes back. 

### Create an annotated tag with tagname v1.7 and push it
![image](https://github.com/menna-abdallah/VirsionControl_2/assets/139376864/0bff7644-ef0b-415c-b8b7-18086c92cf64)
### Tell me how to list tags.
####  git tag 

### Tell me how to delete tag locally and remotely.
#### local:
#### git tag -d v1.7
#### remote:
#### git push origin --delete v1.7

### Add an image in the README.md file
#### using ![alter](image link)
