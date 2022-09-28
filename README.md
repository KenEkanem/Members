# Members

**A github repository to get you started in learning how to make a contribution and create a pull request.**

Use this project to make your first contribution to an open source project on GitHub.

# Make your first pull request by follwing this instructions

## For Beginners
Create a github account, it's free!      
Visit and learn about open source [here!](https://www.digitalocean.com/community/tutorials/what-is-open-source)

## Making your first contributions
### **To do this on gitHub**
- Fork this project by clicking on the fork button at the top right corner of this page
- On your forked repository, click the branch icon with 'main' and create a new branch by typing the name of the branch in the space provided.
- click on create branch: < branch name > 

**Note:** **Branch name is usually related to the purpose the branch was created.**

It's time to edit the CONTRIBUTORS.md file

- Click on the CONTRIBUTORS.md file in the repository
- Click the edit button on the top right corner of the file and add your name to the right location.
- Example: `[FirstName LastName](https://github.com/your-username)`
- Add a commit message and click 'Commit Changes' E.g 'Added[UserName]'
- Make a new pull request - the third option after code and issues under the  repository name or click the green 'compare and pull request button'
See [how to make a pull request](https://github.blog/2015-01-21-how-to-write-the-perfect-pull-request)
- Click 'Make a new pull request' button

**While the base and head repository is auto filled (make sure you're comparing the right branch on the base repository and your head repository)**

- Make sure you click on your head repository's `compare` dropdown, and change from your 'main' branch to your `<new branch name>` if you are not on the right branch
- Confirm the title pull request and click create 'pull request button'        
 ***Congratulations***!




### **To do this on your local machine**
- Open terminal
- Install git on your machine if you don't already have it
- Fork the project on github
- Clone the project by copying the http or ssh link in your new repository
```bash
git clone https://github.com/YOUR_USERNAME/Members.git
```
- Navigate to the cloned folder
```bash
cd Members
```
- Create a new branch by doing
```bash
  git checkout -b <name-of-new-branch>
```
- open the CONTRIBUTORS.md file with any text editor
- Add your name and github URL to the right location

- Example: `[FirstName LastName](https://github.com/your-username)`

 - Stage your changes.

```bash
  git add CONTRIBUTORS.md
```
- Commit the changes with a commit message using this format

```bash
  git commit -m "Added<YOUR_GITHUB_USERNAME"
```
- Push to a new branch on github
```bash
  git push origin <name-of-your-branch>
```
- Make a new pull request - the third option after code and issues under the  repository name or click the green 'compare and pull request button'. Also see [how to make a pull request](https://github.blog/2015-01-21-how-to-write-the-perfect-pull-request)
- Click 'make a new pull request' button

**While the base and head repository is auto filled (make sure you're comparing the right branch on the base repository and your head repository)**

- Make sure you click on your head repository's `compare` dropdown, and change from your 'main' branch to your `<new branch name>` if you are not on the right branch
- Confirm the title pull request and click create 'pull request button'              
***Congratulations!***


