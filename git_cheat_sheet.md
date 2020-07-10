Fixed unrelated history for git :
`git pull origin master --allow-unrelated-histories`

Restoring a commit to source :
`git restore --source <commit ID>`

making changes to a previous commit and making it a new branch :
`git branch <new-branch-name> acbf019`

If Origin (that references to Fork) is missing certain commands might not work properly. Therefore, in this step, we will be adding an Origin manually. In order to do that: ` git remote -v `

check to see if there is a remote named "Origin" listed. if not, it means that your "Origin" is missing. then you can add origin using : ` git remote add origin <URL> `