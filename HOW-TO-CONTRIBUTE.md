# How to Make a Pull Request  

Every expert was once a beginner! If you're new to making a pull request or facing difficulties, don’t worry—we’re here to help.  

## Prerequisites  
Before getting started, make sure you have:  
1. **A GitHub account**.  
2. **[Git](https://git-scm.com/) installed on your computer**.  

## Steps to Make a Pull Request  

### Step 1: Fork the Repository  
Click the **Fork** button at the top right of the repository page to create a copy under your GitHub account.  

### Step 2: Clone the Repository  
Use Git Bash to clone the forked repository onto your local machine.  

```bash
git clone <repo-link>
```  

### Step 3: Create a New Branch  
Before making changes, create and switch to a new branch.  

```bash
git checkout -b my-branch
```  

### Step 4: Make Your Contribution  
- Add your AI resource to the relevant section with description.  
- Open the `CONTRIBUTORS.md` file and add your name at the bottom of the list.  

### Step 5: Commit and Push Your Changes  
Once you've made your changes, stage, commit, and push them to your branch.  

```bash
git add .
git commit -m "Added my name to CONTRIBUTORS.md and AI resource"
# try and use https://www.conventionalcommits.org/en/v1.0.0/ for commit messages conventions
git push origin my-branch
```  

### Step 6: Create a Pull Request  
1. Navigate to your forked repository on GitHub.  
2. Click **Compare & pull request**.  
3. Provide a meaningful title and description for your contribution.  
4. Click **Create pull request**.  

### Step 7: Celebrate 🎉  
Congratulations! You’ve successfully made a contribution to the **VAM-AIR GitHub repository**.  

If you need any assistance, feel free to reach out. Happy coding 🚀  

