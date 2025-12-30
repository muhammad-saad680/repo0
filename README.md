Experiment 1-4;
mkdir dir_name;
cd dir_name;
git init;
gedit file.txt;
git add file.txt;
git commit -m "message";
git checkout -b feature_branch;
git checkout master;
git stash save "Stash message";
git stash apply;
git clone URL;
cd ~/git1;
 
Experiment 7;
	git tag v1.0;
 
Experiment 8;
	$ git cherry-pick ABC123^..DEF456;
 
Experiment 9;
	git log;
	git show commit_id;
 
Experiment 10;
	$ git log --author="JohnDoe" --since="2023-01-01" --until="2023-12-31";
 
Experiment 11;
	git log -n 5;
 
Experiment 12;
	$ git revert abc123;
Experiment 5;
	git clone <repo_link>;
	git remote add origin <repo_link>;
	gir remote set-url origin <token@repol_link>;
	git checkout master;
	git fetch origin;
	git rebase origin/master;
	git push origin master;
 
Experiment 5;
mkdir exp5;
cd exp5;
git init;
echo "Initial file" > file.txt;
git add file.txt;
git commit -m "Initial commit";
git remote add origin https://github.com/username/repository.git;
git branch;
git checkout master;
git fetch origin;
git rebase origin/master;
git rebase --continue;
git push origin master;
