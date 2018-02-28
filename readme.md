git init 								// create repository

git add . 								//adds all files to repository, must add before commit

git commit 								//basic commit

git commit -a -m "makes a comment" 		//commit all files with comment

git status 								//checks the status of all files

git remote -v 							//gives you the names of all remotes i.e. github

git remote add origin master *url* 		// this adds the remote for the repository to 																	// allow communication to github

git push 								// basic push - sends files along to github

git push origin master 					// you must push to the remote then the branch 
					   					// i.e.(git push *remote-name* *branch-name*)

//BRANCHES

Master 									// is the defualt git branch

gh-pages 								// will host your files as if on a website