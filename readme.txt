1.	Open git console in root directory of your project and do next steps.
2.	Do all your experiments in folder “task1 – git pracrice I”.
3.	Create empty readme.txt file.
4.	Make init commit.
5.	Create develop branch and checkout on it.
6.	Create index.html empty file. Commit.
7.	Create branch with name “images”. Checkout on it. Add images folder with some images inside it. Commit.
8.	Change your index.html. Add images source inside it. Commit.
9.	Go back to develop branch.
10.	Create branch with name “styles”. Checkout on it.  Add styles folder with styles source inside it. Commit.
11.	Change your index.html. Commit.
12.	Go to develop branch.
13.	Merge two new branches into develop using git merge command. Resolve conflict if it appear. Do it in next sequence:
●	merge “images” into “develop”
●	merge “styles” into “develop”
14.	Do not delete any branches!
15.	Merge develop into master.
16.	Checkout to develop branch and repeat 7-15 items once more (use names “images2”, “styles2” for new branches). Now use git rebase command instead of git merge in step 13. Do rebase in next sequence:
●	rebase “images2” onto “develop”
●	rebase (fast-forward) “develop” onto “images2”
●	rebase “styles2” onto ‘’develop’
●	rebase (fast-forward) “develop” onto “styles2”
17.	Merge develop into master.
NOTE: As a result master/develop branches should contain all commits that were done in process
