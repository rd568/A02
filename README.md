<h1>Git Tutorial</h1>

<h3>1. Install and Set Up Git</h3>

<ul><li>Download Git from Git's website.</li>
<li>Check if Git is installed by opening a terminal and typing git --version.</li></ul>
<h4>Set up your info:</h4>

<ul><li>git config --global user.name "Your Name"</li>
<li>git config --global user.email "your.email@example.com"</li>
</ul>
<h3>2. Use Git with GitHub</h3>
<ul><li>Log in to GitHub and create a new repository by clicking New repository.</li>
<li>Name your repository and click Create.</li>
</ul>
 <br />
<h4>Copy the repository to Git:</h4>
<br />
git clone https://github.com/your-username/repository -name.git

<br />
<h3>3. Make and Save Changes</h3>


<h4>Check status:</h4>
git status

<h4>Add changes:</h4>
git add .

<h4>Save changes:</h4>
git commit -m "Your message"

<h4>Upload changes to GitHub:</h4>
git push origin main

<h3>4. Get Updates from GitHub</h3>
<h4>Pull changes:</h4>
git pull origin main


<h1>VS Code Tutorial</h1>
<h3>Open a Git Repository in VS Code</h3>
<ul><li>Open VS Code.</li>
<li>Install VS Code </li>
<li>Go to File > Open Folder and select your Git repository.</li>

<li>Open the Source Control panel (click the Git icon in the sidebar or press Ctrl + Shift + G).</li></ul>

<h3>Make Changes and Commit in VS Code</h3>
<ul><li>Edit your files in VS Code.</li>

<li>Open the Source Control panel.</li>

<li>Click the + next to the changed files to stage them.</li>

<li>Write a commit message and click Commit.</li></ul>

<h3>Sync with GitHub</h3>
<ul><li>In the Source Control panel, click Pull, Push, or Sync Changes to update your repository.</li></ul><br />

<h3>Handle Merge Conflicts</h3>
<ul><li>If there’s a conflict, Git will mark the conflicting files.</li>

<li>Open the file in VS Code and look for conflict markers (<<<<<<<, =======, >>>>>>>).</li>

<li>Decide which changes to keep and delete the conflict markers.</li>

<li>Save the file, stage it (git add filename), and commit (git commit -m "Resolved conflict").</li></ul>




<br />
<h1>Glossary</h1>

<ul><li> <b>Branch</b> - A parallel version of a repository that allows developers to work on new features or fixes without affecting the main codebase.
</li>
<li><b>Clone</b> -  A copy of a remote repository downloaded to a local machine, allowing you to work on it independently.</li>

<li><b>Commit</b> - A snapshot of changes made to a repository, saved with a unique ID and a message describing the update.</li>


<li><b>Fetch</b> - A command that retrieves the latest changes from a remote repository but does not apply them to the local branch.</li>

<li><b>GIT</b> - A distributed version control system that tracks changes in code and allows multiple developers to collaborate efficiently.</li>

<li><b>Github</b> - A cloud-based platform for hosting Git repositories, enabling collaboration, code review, and version control.</li>


<li><b>Merge</b> - The process of combining changes from one branch into another, usually integrating new features or fixes into the main codebase.</li>

<li><b>Merge Conflict</b> - A situation that occurs when Git cannot automatically resolve differences between branches, requiring manual intervention to reconcile the changes.</li>

<li> <b>Push</b> - A command that sends local commits to a remote repository, updating it with the latest changes.</li>

<li><b>Pull</b> - A command that fetches the latest changes from a remote repository and merges them into the local branch.</li>

<li><b>Remote</b> - A version of a repository stored on a hosting service like GitHub, allowing collaboration and synchronization between multiple contributors.</li>

<li><b>Repository</b> - A storage location for a project’s files and version history, which can be local or hosted remotely on platforms like GitHub.</li></ul>


