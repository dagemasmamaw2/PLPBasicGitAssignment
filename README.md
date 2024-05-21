# PLPBasicGitAssignment

To initialize local repository 
 
1.	$ git init

To connect the remote repo with the local repo

2.	$ git remote add origin https://github.com/dagemasmamaw2/PLPBasicGitAssignment.git

To change master branch to main branch

3.	$ git branch -M main

To pull read me document from remote repository 

4.	$ git pull origin main

From https://github.com/dagemasmamaw2/PLPBasicGitAssignment
 * branch            main       -> FETCH_HEAD

Create txt file with Hello, Git text

5.	$ echo "Hello, Git!" > hello.txt

Stage the changes by running

6.	$ git add hello.txt

Commit the changes with a message by running

7.	$ git commit -m "Add hello.txt with a greeting"
[main bedf3ca] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

To staging read me file modification

8.	$git add .

Committing the change in read me file

9.	$ git commit -m "Modifying Read Me File"

Push the committed changes to your GitHub repository using

10.	$ git push -u origin main

Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 308 bytes | 308.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/dagemasmamaw2/PLPBasicGitAssignment.git
   0e7495f..bedf3ca  main -> main
branch 'main' set up to track 'origin/main'.

