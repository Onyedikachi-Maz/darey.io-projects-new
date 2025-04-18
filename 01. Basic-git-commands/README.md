# Basic git commands
## How to create a new repository
the image shows the steps involves in creating a new repository
![repository](./img/1.%20creating%20a%20new%20repository.png)

## cloning the repository
after creating a new repository, the new repository is cloned to the local directory of the computer, where the team members will perform their task and then push to the remote repository. Therefore the remote repository's URL is first copied
![copying the URL](./img/2.%20copying%20the%20URL.png)  

creating a new directory

![new directory](./img/3.%20creating%20a%20directory.png)

cloning the remote repository to the local directory
![cloning](./img/4.%20cloning%20the%20repository.png) 

creating a new file index.html
![](./img/6.%20creating%20an%20empty%20file.png)

checking for the status of the file
![](./img/7.%20checking%20for%20status.png)

git adding the new file. that is staging the file
![](./img/8.%20git%20add.png)

confirming the status of the file
![status](./img/9.%20confirming%20changes.png)

committing the changes using ``git commit -m ''this is my first commit``
![](./img/10.%20git%20commit.png)

pushing the file to the remote repository using ``git push origin main``
![](./img/11.%20git%20push.png)

After pushing the file to the remote repository, the branch status is checked so as to know the current branch we are on.
![](./img/12.%20checking%20current%20branch.png)

A new branch is created by Tom so he can perform his task using ``git git checkout -b update navigation`` 
![](./img/13.%20creating%20a%20new%20branch.png)

confirming the new branch created using ``git branch``
![](./img/14.%20confirming%20new%20branch%20created.png)

The file was updated by Tom in the new branch created before stagging the changes to the file using ``git add index.html``
![](./img/15.%20stagging%20tom's%20update.png)

committing the changes using ``git commit -m ''update navigation bar''``
![commit](./img/16.%20commiting%20tom's%20work.png)

The changes are being pushed to the remote repository using ``git push origin update navigation``
![push](./img/17.%20pushing%20tom's%20work.png)

## Jerry's contribution
After Tom's contribution, we switch to the main branch to create a new branch for Jerry.
![](./img/18.%20switching%20to%20the%20main%20branch.png)

The command ``git pull is used to pull the latest changes from Tom's work``
![pull](./img/19.%20git%20pulling%20the%20latest%20changes.png)

The command ``git checkout -b add-contact-info`` is use to create a new branch for Jerry's work
![new branch](./img/20.%20creating%20a%20new%20branch%20for%20jerry's%20work.png)

The command ``code index.html``was used to open text editor to make changes on jerry's work.
![changes](./img/21.%20updating%20jerry's%20work.png)

After making changes to Jerry's work, the command ``git add index.html``
![add](./img/22.%20staging%20jerry's%20work.png)

committing the changes with the command ``git commit -m "Add contact information"``
![commit](./img/23.%20commiting%20jerry's%20work.png)
The changes are pushed to the remote repository with the command ``git push origin add-contact-info``
![push](./img/24.%20git%20pushing%20jerry's%20work.png)