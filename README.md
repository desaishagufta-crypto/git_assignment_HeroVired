Repository Link: https://github.com/desaishagufta-crypto/git_assignment_HeroVired

Question 1: CalculatorPlus Application
1a. Repository Creation
Created a private GitHub repository named "git_assignment_HeroVired" through GitHub web interface.

1b. Development Branch Setup
Created a 'dev' branch from main and added the complete Calculator class with all basic arithmetic operations (add, subtract, multiply, divide) plus the newly implemented square_root function using the math library.

1c. Version 1 Release
Merged the 'dev' branch into 'main' through a pull request on GitHub and created the first release tagged as v1.0.0 containing the basic calculator functionality with square root support.

1d. Team Collaboration
Added a classmate as a collaborator to the repository with write permissions to enable team contributions and code reviews.

1e-f. Feature Development
Created a new feature branch called 'feature/sqrt' to implement and test the square root functionality independently from the main development flow.

1g. Bug Fix During Feature Development
While working on the square root feature, received a critical bug report about division by zero. Temporarily stashed the feature work, switched to 'dev' branch, created a hotfix branch 'hotfix/divide-by-zero', implemented the fix to raise ValueError when dividing by zero, merged the hotfix into 'dev', then rebased the 'feature/sqrt' branch to keep it updated with the bug fix.

1h-i. Pull Request and Code Review
Created a pull request from 'feature/sqrt' targeting main branch, requested code review from team member, implemented suggested improvements based on review feedback.

1j. Feature Integration
After code review approval, changed the pull request target to 'dev' branch and successfully merged the square root feature into development.

1k. Final Release
Tested the complete application in 'dev' branch, created a pull request from 'dev' to 'main', merged changes, and created version 2.0.0 release containing square root feature and divide-by-zero protection.

Question 2: Git LFS Integration
LFS Branch Creation
Created a dedicated branch named 'lfs' to demonstrate Git Large File Storage capabilities.

Large File Handling
Installed Git LFS, configured it to track specific large file types, uploaded a binary file larger than 200MB, committed the file along with LFS configuration, and successfully pushed to remote repository.

Verification Process
Cloned the repository on a separate machine and confirmed that Git LFS correctly downloaded the large binary file, proving proper LFS integration and functionality.

Question 3: Geometry Calculator with Git Stash Workflow
Base Branch Setup
Created 'geometry-calculator' branch and added the GeometryCalculator class skeleton with circle and rectangle area calculation methods.

Feature Branch 1 - Circle Area
Created 'feature/circle-area' branch, began implementing circle area calculation, intentionally left it incomplete, and used git stash to save the work-in-progress changes before switching branches.

Feature Branch 2 - Rectangle Area
Returned to base branch, created 'feature/rectangle-area' branch, started rectangle area implementation, stashed the incomplete work to demonstrate switching between multiple unfinished features.

Stash Workflow Demonstration
Switched back to 'feature/circle-area', retrieved stashed circle changes using git stash pop, completed the circle area feature implementation, committed, and pushed to remote.

Rectangle Feature Completion
Switched to 'feature/rectangle-area', retrieved stashed rectangle changes, completed rectangle area feature, committed, and pushed to remote.

Pull Request Workflow
Created two separate pull requests targeting the 'dev' branch - one for circle area feature and one for rectangle area feature. Added classmate as reviewer for both pull requests.

Review and Merge Process
After receiving code review approval from team member, merged both feature pull requests into 'dev' branch, then created a final pull request from 'dev' to 'main' branch and completed the merge.

Additional Requirements Completed
Team Collaboration: Added classmate as repository collaborator and provided code review for at least one classmate's repository.

Documentation: All steps clearly documented in this README file with explanation of each task completed.

Repository Status: Maintained as private repository during assignment period as per submission guidelines.

Note: This document serves as complete documentation of all assignment requirements. Repository contains all source code files, branches, releases, and Git history demonstrating the complete workflow from initial setup through feature development, bug fixes, code reviews, and final releases.
