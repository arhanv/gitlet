# gitlet
Functional version-control system based on Git

I completed this project for the core Data Structures and Algorithms class at Berkeley. Due to academic honesty rules, I can't share the entire project here, but here are some details:

[Project Spec](https://sp21.datastructur.es/materials/proj/proj2/proj2)

We were tasked with building this project from scratch in Java. There was no code skeleton, apart from the `main` method and a few empty `util` files. The features I ultimately implemented were:
* `init`,`add`,`commit` - which facilitate the initialization of new repositories, adding files to the staging area and committing file modifications.
* `rm`,`log`,`global-log`,`find`,`status`,`checkout` - which deal with reverting modifications and tracking changes across multiple versions.
* `branch`,`rm-branch` - which enable several simultaneous streams of file-versions to co-exist in the repository.
* `reset`, `checkout` - operational commands that are essential to prioritizing and finalizing changes in the files.
* `merge` - which, much like the real Git, incorporates changes from various branches into a singular file history.
* `add-remote`, `rm-remote`, `push`, `fetch`, `pull` - which extend the capabilities of Gitlet to remote file tracking and version-control across multiple file systems.
