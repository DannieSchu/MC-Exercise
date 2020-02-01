# MC-Exercise

After each team's changes were accepted and merged, Bob and Carol just created a new local branch instead of pulling from the remote master branch into their local feature branch. As a result, the version of the repo they were contributing to was not the freshly merged code that their teammates were working on. 

When they attempted to merge, the two versions were in conflict. To resolve this, we removed the redundancies, eliminated markers, and got our laptops in sync with a new git pull origin master into our local master branches. Instead of working on local feature branches, however, we each worked on our local master branches. When we attempted to push to the remote master branch, we encountered another merge conflict! Since Bob and Carol had already pushed their local master changes onto the remote master, Ted and Alice were unable to push. Ted resolved this conflict by re-pulling the other team's fresh code from the remote master branch.
