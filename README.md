# Useful `.gitignore` for data analytics workflows

Copy the content of a given `*.gitignore` file into your repository `.gitignore`. Then execute the following git commands in the terminal in order to add files to the ignored ones and remove them from future committs.

````
git rm -r --cached .
git add .
git commit -m "fixed untracked files"
git push
````
*Be sure to execute the commands in the git repository folder.
