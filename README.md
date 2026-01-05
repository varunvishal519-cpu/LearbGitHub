# LearbGitHub
<br>
Author :- Varun Vishal(Trying againf)
<br>
<p>git config --global user.name "xyz-cpu"</p>    <!--command to create global user name to commit code -->
<p>git config --global user.email "xyz@gmail.com"</p><!--coomand to create global email to commit code-->
<p>git config user.name "abx"</p><!--command to create local user name to commit code -->
<p>git config user.email "abc@example.com"</p><!--coomand to create local email to commit code-->
<p>To check what we have config :- git config --list</p>

<p><b>Step to work with git</p>
<br>
<p>git clone https://github.com/your-username/your-repo.git </p><!--clone code which is also called local repo-->
<p>git status </p> <!--to check the status -->
 <p>git add . </p>  <!--add all the files for commit in local repo -->
<p>git commit -m "any meanigfull message here" </p><!--commit code on local repo-->
<p>git push origin 'main' </p><!--Tu push the local changes to origin or 'main' branch on github-->


# To add project from system to github repositry (Local to Remote )

<p>git init</p><!--to initiate or make system code as git-->
<p>git add .</p>
<p>git commit -m "saome usefull meassaged"</p>
<!-- then create a repo on git hub like constructionwork and anything u want-->
<p>git add remote origin https://github.com/your-username/your-repo.git</p> <!-- to set the "origin" name (if we wanted we can set origin name to anything we want ex : "git add remote cons https://github.com/your-username/your-repo.git" then to push we can write "git push cons main" )-->
<p>git remote -v</p> <!--to check git remote-->
<p>git branch</p> <!-- to check the code is on which branch-->
<p>git branch -M 'main'</p><!--to change the branch name to "main"-->
<p>git push origin 'main'</p> <!--to push the code to remote or main brach or github-->



# Git Branches

<p>git branch</p> <!--to check branch-->
<p>git branch -m main</p><!--to change the braanch name-->
<p>git checkout 'Branch name'</p> <!-- to navigate from one branch to other-->
<p>git ckeckout -b 'Branch name'</p><!-- to create new branch -->
<p>git ckeckout -d 'Branch name'</p><!-- to delete particular branch --> 
<p>git ckeckout -d 'Branch name'</p><!-- to delete particular branch --> 
