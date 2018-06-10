This is a README file about how to creat git repository from scracth.

Please check related website: https://www.jianshu.com/p/db3396474b96

1. Create local repo
	mkdir learngit
	git init
2. Check if local repo created
	ls -ah
3. Commit changes and files
	git add README.txt
	git commit -m "add README FILE"
4. Check logs
	git log
5. SSH key
   check if you have ssh key
	cd ~/.ssh
   if id_rsa & id_rsa.pub exits.
   if NOT, use
	ssh-keygen -t rsa -C "youremail@example.com"
   (use cat ~/.ssh/id_rsa和cat ~/.ssh/id_rsa.pub to check the content)
6. Remote repo
	1) create new repo at github.
	2) go to local, then
		git remote add origin git@github.com:DavidSheh/learngit.git
	3) push local repo to remote, use below for first time 
		git push -u origin master
	  next time, use below to push
		git push origin master
7. Clone (If local does not have remote repo)
	git clone git@github.com:DavidSheh/learngit.git

