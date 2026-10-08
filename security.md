# intended users
This repo is forked from Professor Lamoureux's, therefore it included a CODEOWNERS file already. I added my own github username to the file. This contains coursework for CSE 3000 at UConn. So the intended users would be myself and the instructor, and TA's for grading. It is not intedned for public distribution. 

# Risk assessment
The code in this repo is for class assignments and contains no crednetials or API keys or any connections to any live systems. If it fell into the wrong hands there is no major risk factors except for possibly another student copying the work done for their own assignments. There are no passwords, secrets, or toekns at risnk in this repo either. The overall risk is low since this is not a repo that conatins any high-value assets. 

# Steps to secure

The CODEOWNERS file assigns ownership of all the files to my professor and to myself, so changes are required to be reviewed by the only actual users of the repo. I also set up a branch ruleset on the main branch. It stops the branch from being deleted and blocks force pushes so its history cannot be rewritten. It also makes changes go through a pull request that a code owner has to review before it gets merged.  