## Publish a Local Git Repository to GitHub Using VS Code
### Prerequisites 
1. A GitHub account
2. Git is installed and available in Terminal ('git --version')
3. Visual Studio Code is installed
4. A local Git repository exists on your machine

### Steps
1. **Open the project folder in VS Code**
2. **Navigate to the Source Control panel**
    - Press: Cmd + Shift + G
    - Or, click on the Git Icon in the sidebar
3. **Stage your changes:**
    1. Open the "Repositories" dropdown menu
    2. Click on the ellipsis icon
    3. Navigate to Changes > Stage All Changes  

    Staging changes acts as the waiting room for commits, the feature allows you to choose which changes you want included in your commit, if needed.  

4. **Make a commit**

    1. Open "Changes" dropdown menu to see Staged Changes files 
    2. Enter a descriptive commit message in the text box and press "Commit"
        - Follow any team-based documentation titling here, or develop consistent titling for future reference and publishing
        - Can open "Graph" dropdown to ensure this commit has saved in your List/Tree

5.  **Publish to GitHub**
    1. Back under your "Repositories" dropdown, select the cloud and arrow icon to begin publishing
    2. VS Code will create popup:
      `The extension 'GitHub' wants to sign in using GitHub.`  
    Select "**Allow**"
    3. VS Code will launch a new tab in your web browser
        - If you are already logged in, GitHub will prompt you to continue with current account -> press "Continue" or "Use a different account"
        - If you are not logged in, GitHub will prompt you to do so
    4. Authorize VS Code in GitHub when prompted 
    5. Follow email verification steps
        - This verification will launch VS Code again, with  
        `Publish to GitHub private repository username/repo_name`  
            and  
        `Publish to GitHub public repository username/repo_name`  
    pre-entered in the Command line.
    6. Highlight your selection and press Enter
    7. VS Code will upload to GitHub and deliver pop-up: 
    `Successfuly published the "username/repo_name" repository to GitHub`
    - Select "Open on GitHub" to navigate to your repo on your browser at GitHub.com

Success. You may now edit your repo on GitHub and share with others. 