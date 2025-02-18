### **Step 1: Create a GitHub Repository**

1. Go to [GitHub](https://github.com/) and log in.  
2. Click on the **\+ (New Repository)** button in the top-right corner.  
3. Enter a repository name, description (optional), and choose public or private.  
4. Check the box for **"Add a README file"** (optional).  
5. Click **Create repository**.

---

### **Step 2: Set Up Git Locally**

1. Install Git if you haven’t already:  
   * **Windows**: Download from [git-scm.com](https://git-scm.com/) and install.

**Linux (Ubuntu/Debian)**:

`sudo apt update`  
`sudo apt install git`

* 

**MacOS**:

`brew install git`

* 

Configure your Git username and email:  
bash  
CopyEdit  
`git config --global user.name "Your Name"`  
`git config --global user.email "your-email@example.com"`

---

### **Step 3: Initialize Git in Your Project Folder**

Open a terminal and navigate to your project directory:

`cd path/to/your/project`

1. 

Initialize Git:

`git init`

Link the local repository to GitHub (replace `<your-repo-url>` with your GitHub repo link):

`git remote add origin <your-repo-url>`

---

### **Step 4: Add, Commit, and Push Your Code**

Check the status of your files:

`git status`

Add all files to Git tracking:

`git add .`

Commit your changes with a message:

`git commit -m "Initial commit"`

Push your project on github:

`git branch -M main`  
`git push -u origin main`

---

### **Step 5: Verify Your Project on GitHub**

1. Go to your GitHub repository.  
2. Refresh the page, and you should see your files uploaded.

---

