[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15584119&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?
Version control fundamental concepts are to track and manage changes to software code to the software teams.Github is popular because its a social networking open source site for programmers ,hence facilitates project management and remote collaboration efficiently.
VC help in maintaining project integrity because it stores history of changes and who made them, allowing one to revert or go back to earlier versions of those documents, and understand how contributions by different contributors have changed the project over time.
## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?
 Step 1: Create a repository:
Actiavte New Repository option,Capture "Repository name",Capture "Description"-optional, select Public optuin to allow the repository see by anyone/private if desired, Initialize repository by selecting "ADD a README file", in the "Add.gitignore" option select the one that you are using e.g. VS Code, select MT LIC on the "Choose a license" option and then activate "Create repository" button.Thereafter, confirm if creating a main /creating a branch.
    Step 2: Creating a branch to allow you have different  versions of a repository at one time:
Click the "Code" tab of your created repository.Above the file list, click the dropdown menu that says main, capture your branch name and click Create branch that is showing the captured branch name from main.
    Step 3: Make and commit changes under the created branch.Under the branch you created, click the README.md file,click edit icon, input your desired changes in the editor,click Commit changes button,add mandatory message and then click Commit changes button.
    Step 4: Open a pull request to allow reviews and merging:
Click the Pull requests tab of your main repository,Click New pull request,In the "Example Comparisons box", select the branch you made to compare with main (the original),Look over your changes in the diffs on the Compare page, make sure they're what you want to submit,click Create pull request,capture the title and write a brief description of your changes and then click Create pull request to complete.
    Step 5: Merge your pull request to allow the changes on your branch to be incorporated into main:
At the bottom of the pull request, click Merge pull request to merge the changes into main and click Confirm merge.As a good practice, and click Delete branch.

important decisions:
Know when to create a main and when to create a branch
Use descriptive names and put clear and concise messages for the changes made
Ensure to make pull 
Good practice to delete branch after merging .If you want to make more changes to your project, you can always create a new branch and repeat this process.

## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?
README file is a guide that gives users a detailed description of a project you have worked on.
 README file should be detailed, clear, and concise.Its should include: a title, a description of the project, installation instructions, usage examples, contribution guidelines, license information, contact and Who maintains & contributes to the project.
 README file contributes to effective collaboration by helping you communicate expectations for your project and helps you manage contributions.

## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?
Public repositories are accessible to everyone on the internet while Private repositories are only accessible to you, people you explicitly share access with, and, for organization repositories, certain organization members.
Advantage of public repositories :Public repositories are a great way to show off your skills , shares you ideas with other people ,hence promotes open-source development(  collaboration with the public to build tools or whatever it is you want to build).
Disadvantage of public repositories:make code visible to everyone, which may not be suitable for projects requiring confidentiality or proprietary code.
Advantage of Private repositories:a good option for commercial or other proprietary projects, as well as personal projects that are not ready to be shared with the world.
Disadvantage of Private repositories:Miniminal public contributions to the project
## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?
Once done with the changes click commit changes button .
Then capture the message and then activate commit button to save the changes.
Commits saves your work/project in the specified repository.
Branches are used to have versions and allows comparison with the main folder .Once the changes are confirmed, the two folders can be merged to allow one file for earier management.

## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.
Branching aids in having versions on what is still being worked on to allow commiting changes ,collaborations until its done.It allow working on undone version separately from main until its confirmed as completely done.

Step 1:Creating a branch to allow you have different  versions of a repository at one time:
Click the "Code" tab of your created repository.Above the file list, click the dropdown menu that says main, capture your branch name and click Create branch that is showing the captured branch name from main.
Step 2: Make and commit changes under the created branch.Under the branch you created, click the README.md file,click edit icon, input your desired changes in the editor,click Commit changes button,add mandatory message and then click Commit changes button.
Step 3: Open a pull request to allow reviews and merging:
Click the Pull requests tab of your main repository,Click New pull request,In the "Example Comparisons box", select the branch you made to compare with main (the original),Look over your changes in the diffs on the Compare page, make sure they're what you want to submit,click Create pull request,capture the title and write a brief description of your changes and then click Create pull request to complete.

## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?
Pull request allows reviews and merging
Step 1: Open a pull request to allow reviews and merging:
Click the Pull requests tab of your main repository,Click New pull request,In the "Example Comparisons box", select the branch you made to compare with main (the original),Look over your changes in the diffs on the Compare page, make sure they're what you want to submit,click Create pull request,capture the title and write a brief description of your changes and then click Create pull request to complete.

## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?
Forking concept is to have a new repository that shares code and visibility settings with the original “upstream” repository.Allowing you to work on the code locally, make changes, and contribute to the project without needing continuous internet access.
Forking creates a separate copy on a remote server while cloning downloads the entire repository onto your computer.
The Developer forks a repository, they create a separate copy of the project in their own account. This copy can be freely modified and experimented with, while still keeping the link to the original repository. 
## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.
Issues and project boards helps you track your work on GitHub.
New bugs raised .allocated to specific developers as per thier expertise ,reolved bugs are tested ,test results are captured against each bug and bug closed/reopened. With these information. the project can be gauged with theif on track using the rate of bug resolution, rate of raising new bugs e.t.c.

JIRA
Bugzilla

## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
Common challenges:
Merge Conflicts: The dilemma of Parallel Development Merge conflicts are a frequent hurdle in collaborative development environments, especially when team members are working on the same file simultaneously.
Best practices:
Write good commit messages
Test before committing
Don't commit half-done work
Use branches


