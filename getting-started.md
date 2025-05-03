
# Getting Started with Git and GitHub: A Friendly Guide for Beginners

If you're a technical writer (or aspiring to be one), learning Git and GitHub might sound like something just for developers, but it's actually a game-changer for **anyone** working with content.

Whether you're writing tutorials, documentation, or blog posts, these tools help you **track your work, collaborate with others**, and **present your portfolio professionally online**.

In this beginner-friendly guide, I’ll walk you through what Git and GitHub are, and show you how to set them up and start using them, no coding experience needed! 

----------

## 💡 Git vs GitHub — What’s the Difference?

Let’s clear up the confusion:

-   **Git** is a version control tool that helps you keep track of changes to your files. Think of it like a time machine for your work, you can jump back to earlier versions whenever you need to.
    
-   **GitHub** is a website that works with Git, where you can store your projects online, share them with others, and collaborate in real time.
    

In simple terms:

 **Git** runs on your computer.  
 **GitHub** lives in the cloud.

----------

## ✍️ Why Technical Writers Should Learn Git and GitHub

Even if you’re not writing code, Git and GitHub help you:

-   Track edits and updates to your documents
    
-   Work smoothly with developers and other writers
    
-   Contribute to open-source projects
    
-   Organize and publish Markdown files professionally
    

Also, knowing these tools makes you look serious and skilled.  It's a great confidence booster.

----------

## 🚀 Step-by-Step: Setting Up Git and GitHub

### 1️⃣ Create a GitHub Account

Head over to [https://github.com](https://github.com) and sign up.

-   Pick a **username** you like. Note that it’ll show up in your portfolio links
    
-   Confirm your email and fill out your profile
    

That’s your first step into the GitHub world! 🎉

----------

### 2️⃣ Install Git

#### 🔹 On Windows:

1.  Go to [https://git-scm.com/downloads](https://git-scm.com/downloads)
    
2.  Click the **Windows** download link
    
3.  Run the installer — just leave the default settings
    
4.  When prompted, select:  
    ✅ _“Git from the command line and also from 3rd-party software”_
    
5.  Finish installation
    

Now open **Git Bash** from the Start menu and run:

```bash
git --version 
```

If you see the version number, that means it’s working!

----------

#### 🔸 On Linux (Ubuntu/Debian):

Open your terminal and run:

```bash
sudo apt update
sudo apt install git
```

Then check the version:

```bash
git --version
```

Done! 🎉

----------

### 3️⃣ Set Up Your Git Identity

Let Git know who you are (this info will show up in your commit history):

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
``` 

Check your settings with:
```bash
git config --list
``` 

----------

### 4️⃣ Create Your First GitHub Repository

1.  Log in at [https://github.com](https://github.com)
    
2.  Click the **+ icon** (top right) → **New repository**
    
3.  Give it a name like `tech-writing-portfolio`
    
4.  (Optional) Add a short description
    
5.  ✅ Check **"Initialize this repository with a README"**
    
6.  Click **Create repository**
    

You just created your first online project folder! 🙌

----------

### 5️⃣ Clone the Repo to Your Computer

Now, let’s bring that repo into your local machine.

1.  On your repo page, click the green **Code** button → copy the HTTPS link
    
2.  In your terminal or Git Bash, run:
    
```bash
git clone https://github.com/yourusername/tech-writing-portfolio.git
``` 

3.  Go into the folder:
```bash
cd tech-writing-portfolio
``` 

----------

### 6️⃣ Add Your First Markdown Article

You can create a new Markdown file like this:

```bash
touch getting-started.md
```

Or just open your folder in a text editor like **VS Code**, **Notepad++**, or even plain **Notepad**.

Paste your content, save the file, and you're ready to commit!

----------

### 7️⃣ Commit and Push Your Changes

This is how Git works:

➡️ **Add** the file  
➡️ **Commit** your changes with a message  
➡️ **Push** to upload it to GitHub

Run:
```bash
git add getting-started.md
git commit -m "Add first article: Getting Started with Git and GitHub" 
git push origin main
```

✨ Boom! Your article is now live on your GitHub repo.

----------

## 🧠 Common Git Terms (Made Easy)

-   `git add` – tells Git which file(s) you want to track
    
-   `git commit` – saves your work with a message
    
-   `git push` – uploads your changes to GitHub
    
-   `git pull` – gets the latest changes from GitHub
    
-   `repo` – short for repository; it’s your project folder
    

----------

## Final Thoughts 💬

Git and GitHub can seem intimidating at first, but once you try it a few times, it becomes second nature.
Begin with your next article and keep practicing. Before long, you’ll be managing your portfolio like a pro. 🚀
