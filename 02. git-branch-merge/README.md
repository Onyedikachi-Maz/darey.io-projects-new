# Merging and branching in Git
## creating a pull request for Tom's work
firstly, the update navigation branch needs to be selected in github.
![update navigation](./img/01.%20creating%20pull%20request.png)

After that the open pull request button is selected.
![pull request](./img/02.%20click%20on%20new%20pull%20request.png)

The picture below shows the description of the pull request.
![description](./img/03.%20adding%20description.png)

click on merge pull request.
![merging](./img/04.%20merging%20Tom's%20work.png)

click on confirm merge to merge the branch.
![confirming](./img/05.%20confirming%20merging.png)

For Jerry to work with the latest changes, he needs to pull the latest changes from the origin using the command ``git checkout add-contact-info`` and then ``git pull origin main``

After Tom's branch has been merged to the main branch, Jerry's ``add-contact-info``branch is then selected.
![add-contact-info](./img/06.%20selecting%20Jerry's%20branch.png)

click on on ``open pull request``
![pull request](./img/07.%20creating%20a%20pull%20request.png)

A description needs to be added to the pull request.
![description](./img/08.%20adding%20description.png)

clicking on the ``create pull request button``.
![pull request](./img/09.%20clicking%20on%20the%20pull%20request%20button.png)

click on merge to add Jerry's latest changes to the main branch.
![](./img/10.%20clicking%20on%20merge.png)

confirming the merging of the branch.
![](./img/11.%20confirming%20merge.png)

Finally use this command``git push origin add-contact-info`` to push the latest changes.
