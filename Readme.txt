-cd desktop
-cd IT120_Dumaguin_Act1
-git config --global user.name
-git config --global user.email
-touch Profile.txt Education.txt Background.txt Readme.txt Test.py
-notepad Profile.txt
	 Education.txt
	 Background.txt
	 Readme.txt
	 Test.py
-git init
-git add .
-git commit -m "Added Files Profile.txt Education.txt Background.txt Readme.txt Test.py"
-git status
-git checkout -b Dumaguin_B1
		 Dumaguin_B2
		 Dumaguin_B3
		 Dumaguin_B4
-ls
-git checkout Dumaguin_B1
-notepad Profile.txt
-git add Profile.txt
-git commit -m "Added Profile.txt in Dumaguin_B1 Branch"
-git checkout Dumaguin_B2
-git notepad Education.txt
-git add Education.txt
-git commit -m "Added Education.txt in Dumaguin_B2 Branch"
-git checkout Dumaguin_B3
-notepad Background.txt
-git add Background.txt
-git commit -m "Added Background.txt in Dumaguin_B3 Branch"
-git checkout Dumaguin_B4
-notepad Test.py
-git add Test.py
-git commit -m "Added Test.py in Dumaguin_B4 Branch"
-git checkout Dumaguin_B1
	-git rebase Dumaguin_B2
	-git rebase Dumaguin_B3
	-git rebase Dumaguin_B4
-git checkout Dumaguin_B2
	-git rebase Dumaguin_B1
	-git rebase Dumaguin_B3
	-git rebase Dumaguin_B4
-git checkout Dumaguin_B3
	-git rebase Dumaguin_B1
	-git rebase Dumaguin_B2
	-git rebase Dumaguin_B4
-git checkout Dumaguin_B4
	-git rebase Dumaguin_B1
	-git rebase Dumaguin_B2
	-git rebase Dumaguin_B3

-git checkout Dumaguin_B3
-ls
-git rm Test.py
-git checkout Dumaguin_B4
-git checkout Dumaguin_B3
-git commit -m "remove Test.py in Dumaguin_B3 Branch"
-ls
-git checkout Dumaguin_B4
-git commit -m "remove Test.py in Dumaguin_B4 Branch"
-ls
-git checkout master
-notepad Profile.txt
	 Education.txt
	 Background.txt
	 Readme.txt
	 Test.py
-git checkout Dumaguin_B3
-notepad Readme.txt
-git add Readme.txt
-git commit -m "Add all commands in Readme.txt in Dumaguin_B3 Branch"


