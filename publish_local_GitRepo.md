## Publish a Local Git Repository to GitHub Using VS Code
### Prerequisites 
1. Git installed
2. A GitHub account
3. VS Code installed
4. Access to local project folder

### Steps
1. Open the project folder in VS Code
2. Navigate to the Source Control panel
    - Press: Cmd + Shift + G
    - Or, click on the Git Icon in the sidebar
3. Open the "Repositories" dropdown menu
4. Click on the ellipsis icon
5. Navigate to Changes > Stage All Changes
    - Staging changes acts as the waiting room for commits.
    - The feature allows you to hand-select the modifications you want included in your commit, if needed.
6. Open "Changes" dropdown menu
    - You should now see Staged Changes files here
    - Enter a descriptive commit message in the text box and press "Commit"
        - Follow any team-based documentation titling here, or develop consistent titling for future reference and publishing
        - Can open "Graph" dropdown to ensure this commit has saved in your List/Tree
7. Back under your "Repositories" dropdown, select the cloud and arrow icon to **Publish to GitHub**
8. VS Code will create popup:
    `The extension 'GitHub' wants to sign in using GitHub.`  
    Select "**Allow**"
9. VS Code will launch a new tab in your web browser
    - If you are already logged in, GitHub will prompt you to continue with current account -> press "Continue" or "Use a different account"
    - If you are not logged in, GitHub will prompt you to do so
10. GitHub will now prompt you to authorize VS Code. Review settings and then press "Authorize Visual-Studio-Code" 
11. You will now have to verify access via email, select "Verify via email"
12. Navigate to email, open email from GitHub, copy verification code
13. Paste verification code as prompted by GitHub
14. This verification will launch VS Code again, opening the program with  
    `Publish to GitHub private repository username/repo_name`  
    and  
    `Publish to GitHub public repository username/repo_name`  
    entered into the Search and Command line at the top of the window
    
    Highlight your selection and press Enter
15. VS Code will upload to GitHub and deliver pop-up: 
`Successfuly published the "username/repo_name" repository to GitHub`
    - Select "Open on GitHub" to navigate to your repo on your browser at GitHub.com

16. Success. You may now edit your repo on GitHub and share with others. 