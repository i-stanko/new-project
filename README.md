1. Create a new directory in your environment called "new-project":

	`mkdir new-project`

2. Change to the "new-project" directory:

	`cd new-project`

3. Initialize a new public Git repository inside the "new-project" directory:

	`git init`

4. Create a new file called "README.md" and add the opening text to it:

	`subl README.md`

5. Prepare the "README.md" file for the commit:

	`git add README.md`

6. Commit the changes to the repository with the commit message “init”:

	`git commit -m "init"`

	`git remote add origin https://github.com/i-stanko/new-project.git`

	`git push -u origin main`

7. Create a new branch called "development" and switch to it:

	`git branch development`

	`git checkout development`

8. Add the instructions to the "README.md" file and prepare them for the commit:

	`subl README.md`

	`git add README.md`
