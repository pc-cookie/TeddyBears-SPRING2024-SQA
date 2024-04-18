# Project Report
Part A: 
Added a bandit command on the MLForensics folder in the pre-commit to check for security weaknesses in files. Since the .git/hook folder cannot be pushed to GitHub, the pre-commit file was added to the GitHub repo for other group members to add to their own machines.

Part B: Added a file called fuzz.py to check for errors, found five like asked in the project.md. Running it will give the user a list of failure in crashes of errors. 


Part C: 


Part D: 
Cloned the repository, added the .github/workflows/ directory, then added Codacy using github actions. To do this I created the codacy-analysis.yaml file in the directory mentioned above, then I went to https://github.com/marketplace/actions/codacy-analysis-cli to get the code for the file. Finally I was able to see it running by making a small change to one of the files.
