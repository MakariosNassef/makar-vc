1- creat Repo with name Version-Control-Lab-2

2- mkdir Version-Control-Lab-2 git init git remote add origin https://github.com/NathanEid/Version-Control-Lab-2.git

3- git checkout -b dev #to creat a new branch 3- git checkout -b test #to creat a new branch

4- for push the files into branchs git add . git commit -m "test" git push origin dev #for dev branch git push origin test #for test branch

5- merge my two branchs to master lacaly when i was in master git merge dev git merge test

6- for push my local master to remote with Command line
$ git push origin master with pull request in github

7- to remove a bransh localy & remotely
$ git bransh -d BRANSHNAME  
$ git push origin :BRANSHNAME

8- Create an annotated tag with tagname (v1.7).
$ git tag -a v1.7 -m "New versio v1.7"

9- Push it to the remote repository.
$ git push origin v1.7

10- Tell me how to list tags.
$ git tag

11- Tell me how to delete tag locally and remotely.
$ git tag -d v1.7 git push origin --delete v1.7

12- image

![This is an image](https://www.pngkey.com/png/detail/0-8203_old-batman-logo.png)
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)
