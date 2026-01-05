# LearnGitHub
<br>
<p><b>Author :- Varun Vishal(Trying againf)</b></p>
<br>
<p>Git Command to set global and loacal user to clone Project and how to add ,commit and push in a github repositry</p>
<ul>
<li>git config --global user.name 'xyz-cpu'</li>    <!--command to create global user name to commit code -->
<li>git config --global user.email 'xyz@gmail.com'</li><!--coomand to create global email to commit code-->
<li>git config user.name 'abx'</li><!--command to create local user name to commit code -->
<li>git config user.email 'abc@example.com'</li><!--coomand to create local email to commit code-->
<li>To check what we have config : git config --list</li>


<li>git clone https://github.com/your-username/your-repo.git </li><!--clone code which is also called local repo-->
<li>git status </li> <!--to check the status -->
<li>git add . </li>  <!--add all the files for commit in local repo -->
<li>git commit -m "any meanigfull message here" </li><!--commit code on local repo-->
<li>git push origin 'main' </li><!--Tu push the local changes to origin or 'main' branch on github-->
</ul>


# To add project from system to github repositry (Local to Remote )
<p><b>Git Command to add project from local system to git repositry</b></p>
<ul>
<li>git init</li><!--to initiate or make system code as git-->
<li>git add .</li>
<li>git commit -m 'some usefull meassag'</li>
<!-- then create a repo on git hub like constructionwork and anything u want-->
<li>git add remote origin https://github.com/your-username/your-repo.git</li> <!-- to set the "origin" name (if we wanted we can set origin name to anything we want ex : "git add remote cons https://github.com/your-username/your-repo.git" then to push we can write "git push cons main" )-->
<li>git remote -v</li> <!--to check git remote-->
<li>git branch</li> <!-- to check the code is on which branch-->
<li>git branch -M 'main'</li><!--to change the branch name to "main"-->
<li>git push origin 'main'</li> <!--to push the code to remote or main brach or github-->
</ul>



# Git Branches
<p><b>Git Command to create new branches and navigate on it and delete it</b></p>
<ul>
<li>git branch</li> <!--to check branch-->
<li>git branch -m main</li><!--to change the braanch name-->
<li>git checkout 'Branch name'</li> <!-- to navigate from one branch to other-->
<li>git ckeckout -b 'Branch name'</li><!-- to create new branch -->
<li>git ckeckout -d 'Branch name'</li><!-- to delete particular branch --> 
</ul>

# Merge Branch

<p><b>Way 1</b><p>
<ul>
<li>git diff 'branch name'</li> <!--to compare commits,branches,files,manymore-->
<li>git merge 'branch name'</li> <!-- to merge two branches (But genearally we use pull request to merge anuthing)-->
<li>
</ul>

<p><b>Way 2</b></p>
<ul>
<li>through PR (Pull request)</li>
</ul>


# Pull request

<p>It lets you tell other about the changes u have pushed to a branch in a repositry or github</li>

# Pull command

<p>git pull origin main : (used to fetch or download content from remote repo and immediately update the local repo to match the content)</li>


# Undoing Changes

<p>Case 1 : staged changes (which is att add . stage)</li>
<ul>
  <li>git reset 'file name'</li> <!-- to reset the file which is at add . stage-->
  <li>git reset</li><!--to reset all the files at add. stage-->
</ul>
<br>
<p>Case 2 : commited change (for one commit)</li>
<ul>
   <li>git reset head~1</li>
</ul>

<p>Case 2 : commited change (for many commit)</li>
<ul>
   <li>git reset 'commit hash'</li> <!--u can get hash by using 'git log'-->
   <li>git reset --hard 'commit hash'</li><!--even to remove the commits from ur vs code or files-->
</ul>