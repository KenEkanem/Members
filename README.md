# Members

Use this project to make your first contribution to an open source project on GitHub.

# Make your first pull request by follwing this instructions

## For Beginners
Visit and learn about open source [here](https://www.digitalocean.com/community/tutorials/what-is-open-source)

## Making your first contributions
### To do this on gitHub
- Fork this project by clicking on the fork button at the top right corner of this page
- On your forked repository, click the branch icon with 'main' and create a new branch by typing the name of the branch in the space provided.
- click on create branch: < branch name > 

**Note:** **Branch name is usually related to the purpose the branch was created.**

It's time to edit the LIST.md file
- Click on the list.md file in the repository
- Click the edit button on the top right corner of the file and add your name to the right location.
- Add a commit message and click 'Commit Changes'

### To do this on your local machine
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
- open the LIST.md file
- Add your name and github URL to the right location

- Example: `[FirstName LastName](https://github.com/your-username)`

 - Stage your changes.

```bash
  git add LIST.md
```
- Commit the changes with a commit message using this format

```bash
  git commit -m "Added <YOUR_GITHUB_USERNAME"
```