Instruction on setting up local folder to the repo
------------------ 
git init
git add filename
git commit -m "first commit"
-- Tell git that my remote is the origin at https
-- To hook my local environment to the cloud.
git remote add origin https://github.com/pshende2141/Learn.git
-- Push a code locally from origin to master.
-- from master --> origin (which is def in previous command)
git push -u origin master