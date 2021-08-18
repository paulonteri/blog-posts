## How to contribute to Open-Source software with Git & GitHub


![0_hv4ETHKODqYaZmIc.jpeg](https://cdn.hashnode.com/res/hashnode/image/upload/v1626015174339/YuA84Bmyj.jpeg)

This article was posted on the Noteworthy blog:

%[https://blog.usejournal.com/how-to-contribute-to-open-source-software-with-git-github-2b3be6e36c82]

### Table of Contents:

1. Open-Source Software.
    - What is open-source software?
    - Why contribute to open source?
    - How can you contribute to Open-source Software?
2. What is Git & GitHub?
3. Getting Started: Contributing to Open Source Software with Git and GitHub.
    - Find an *open-source project* to contribute to.
    - *Fork* a repository.
    - Create a *branch*.
    - *Cloning* a repository.
    - Making the changes.
    - *Add* & *Commit* the Changes
    - *Push* the changes.
    - Make a* Pull Request(PR)*
4. Final Remarks.

## Open Source Software.

### What is open-source software?
> **Open**-**source software** (OSS) is a type of computer software in which **source** code is released under a license in which the copyright holder grants users the rights to study, change, and distribute the **software** to anyone and for any purpose…
> - Wikipedia.

In a nutshell, open-source software is software with source code that anyone can inspect, modify, and enhance. It is mostly designed to be publicly accessible, anyone can see, modify, and distribute the code as they see fit.

![Photo by [Chris Barbalis](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059394246/Tf13XBn-g.html) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)](https://cdn-images-1.medium.com/max/11448/0*VLZd-qDjoVBQB4mA)

From the earliest days of computers, programmers developed software through collaboration. For instance, a programmer in Kenya develops a new application, then another programmer in the Netherlands studies the application and discovers ways to improve it. The knowledge is shared, and the entire community benefits from the collective growth.

However, open-source software isn’t exactly **free software**, Companies may still sell services and products related to open-source software. For instance, they can offer a premium version of the software that has additional features.
> Fun fact: 96% of all code contains open-source code!!

Open-source is a cornerstone of software development and its impossible to imagine a past, present or future without open-source software.

## Why contribute to open source?

I have always been the person to `pip install`, `npm install` or `git clone` a piece of software without really thinking about the creators or maintainers. I’ve never really thought about how I can contribute to the projects and the benefits that will be pushed my way as a result of that.

What about you?
> Have you ever wondered why both the largest and smallest companies greatly contribute to open-source?
> Have you asked yourself why most developers actively contribute to open-source?

In June of 2019, Tidelift and The New Stack jointly fielded a [survey](https://cdn2.hubspot.net/hubfs/4008838/Resources/The-2019-Tidelift-managed-open-source-survey-results.pdf) of **professional software developers**. It was really interesting that **most developers (84%)** view themselves as **active contributors to open-source** projects.

A similar analysis was done for companies on GitHub:

![The Top 10 Companies Contributing to Open Source as per 2017. Source: [whitesourcesoftware.com](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059397032/jOG0XqWHT.html)](https://cdn-images-1.medium.com/max/2000/1*yFuX0qtgq7u_yeKRqGfBbQ.png)*The Top 10 Companies Contributing to Open Source as per 2017. Source: [whitesourcesoftware.com](https://resources.whitesourcesoftware.com/blog-whitesource/git-much-the-top-10-companies-contributing-to-open-source)*

From the graph above, it’s pretty clear that some of the **most successful and influential technology companies** are serious about **actively contributing to open-source**.

### Why??

### Further Your Career

When you contribute to open source, you are recognized, you sharpen your programming skills, and become part of the vibrant community. This makes you very visible to potential employers. In a [2016 report from the Linux Foundation](https://www2.thelinuxfoundation.org/download-2016-open-source-jobs-report), **86 per cent of technology professionals** said that **open source had helped them thrive in their careers**.
> “When it comes to **hiring** developers, I’ll take a **GitHub commit log over a resume** any day.”
> - John Resig

### To Gain Competitive Advantage

That seems a little counter-intuitive because anyone can use open-source code. However, organizations say that when their developers are writing code for a project, they **get to know the software better** than those who only use it. Some companies can leverage that expertise in ways that benefit their bottom line.

### Reduce Development Costs and Time

When persons or organizations open source an application that originated in-house, they can access a much larger community of developers. Instead of relying only on their team members, they **get contributions from many different people** who are all interested in making the software better.

### Build an Awesome Portfolio

Many companies are looking to hire talent with skills related to specific open source projects, and there are few better ways to **demonstrate your expertise** than by actually having written some of the code for a project.
Your contributions to open source projects will clearly show your **skill**, **reliability** and **motivation. **Open source gives you recognition.

Why do you think you are asked for your **GitHub account** when applying for a technical role?

### Interact with your Mentors, experienced developers and the community at large

Working on an open-source project might allow you to work with some of the best creators in the world. You will now have a common interest and most likely work on it together.

## How can you contribute to Open-source Software?

1. Create your **own open-source project** and host it somewhere public like GitHub.

1. Create **open-source alternatives** to commercial software.

1. Contribute to **existing open-source projects**. This can be done through contributing to the software, design, documentation, community or writing articles like the one you are **currently reading**.
This is what we will be majorly focusing on in this article.

## What is Git and GitHub?

Have you ever collaborated on a project or on a certain document with someone else that may be stored in someplace like Google Drive? How did you track the changes? How did you know who changed what and when? What about versions? How easy was it to collaborate? This will most likely land you in a mess. 😅😅

It must have been such a struggle to collaborate in that manner. I wouldn’t wish such on my worst enemy.

This is where **Git** comes in. To solve all these problems and more…

![Photo by [Sai Kiran Anagani](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059399124/ixUuEmzb_.html) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)](https://cdn-images-1.medium.com/max/12000/0*lgObaY9rglFjch8N)

> **Git** is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows.
> - Wikipedia

In English,*** Git*** is a **version control** tool that is used to track changes in files or source code including what specifically has been changed, who has changed what and when. Git allows a team of people to work together, all using the same files. It helps the team cope with the confusion that tends to happen when multiple people are editing the same files.
> **Version control** systems are software tools that help a software team manage changes to source** **code over time. Version control software keeps track of every modification to the code in a special kind of database

By far, Git is the most widely used modern version control system in the world. It is a mature, actively maintained **open-source** project originally developed in 2005 by *Linus Torvalds*, the famous creator of the Linux operating system.

***GitHub,* **on the other hand, is an online service to which developers who use Git can connect and upload or download resources. *An online hub for Git.*

Founded in April 2008, GitHub is like a *“ Facebook for software development”. *It is a very nice platform for anyone to check out, contribute to and get involved in the open-source community. You’ll meet the creators of your favourite projects, developers, designers, project managers, e.t.c and even get to work with them.

Using GitHub regularly can help you learn how to work well in a development team environment.
> **GitHub** is a Git hosting repository that provides developers with tools to ship better code through command line features, issues (threaded discussions), pull requests, code review, or the use of a collection of free and for-purchase apps in the GitHub Marketplace. With a collaboration community of over 15 million developers and an ecosystem with hundreds of integrations, GitHub changes the way software is built.
> - GitHub.com

## Getting started: Contributing to Open Source Software with Git and GitHub.

This is the most interesting part.

*Prerequisites:*

* *Ensure you have used a computer before this.*

* *Ensure you [install git](https://www.atlassian.com/git/tutorials/install-git).*

* *Create a [GitHub account](https://github.com/join).*

*Confirm you have Git installed by checking the version of Git installed on your device by running this command on your terminal or command line. ( Windows/Mac/Linux )*

```
git --version
```


![[My GitHub Profile](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059402714/13XEr8Pza.html). There is a very huge chance that the background on yours will be white.](https://cdn-images-1.medium.com/max/2356/1*Bnr_qSuiDIL14l-8tMu6-Q.png)*[My GitHub Profile](https://github.com/paulonteri). There is a very huge chance that the background on yours will be white.*

### 1. Find an open-source project to contribute to.

Try to find a friend’s project or even try out [one of my projects](https://github.com/paulonteri?tab=repositories) for the sake of learning. Just go to their profile then navigate to **repositories.**
> A **repository** is like a folder for your project. Your project’s** **repository contains all of your project’s files and stores each file’s revision history. … For user-owned repositories, you can give other people collaborator access so that they can collaborate on your project.
> A **repository **is like a ‘fancy name’ for a** **folder.

![The Repositories tab on a profile.](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059404424/DtirYA-05.png)*The Repositories tab on a profile.*

If you can see a page similar to the one above, you are good to go. 🙂

I am currently interested in the ‘Website’ repository shown above.

### 2. Fork a repository. 🍴
> A** fork** is a copy of a repository. **Forking** a repository allows you to freely experiment with changes without affecting the original project.

![Photo Credits: GitHub.com](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059406160/qfhlvHtqA.jpeg)*Photo Credits: GitHub.com*

When you click the ***fork ***button in GitHub, you are duplicating the entire repository and its history up until that point in time. You make a copy of the repository (the one being forked) into your own GitHub account.

*How to fork a repository:*

* *Navigate to the repository you want to work on and open it. ( In my case, the ‘Website’ repository from oigara’s account)*

* *Click the **Fork button** located at the top right area of the page.*

In my case, I’ll fork the website repository. It’s as simple as clicking on the Fork button as shown below.

![**Before Forking**( The fork button is under the mouse pointer )](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059408031/m9dfqLHLX.png)***Before Forking***( The fork button is under the mouse pointer )

Notice that GitHub automatically navigates to your account after forking. For example, mine navigated from ***oigara/Website*** (the original account and repository) to ***paulonteri/Website*** (my account and the forked repository).

![**After Forking**](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059409776/hwtSBPaB7.png)***After Forking***

That’s it — after forking, you’ll have a copy of the original repository in your GitHub account.

### 3. Create a branch.
> A **branch** is a version of the repository that diverges from the main working project. Essentially an almost new and independent line of development.

![Photo by [Zach Reiner](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059411662/-lnwuGO21.html) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)](https://cdn-images-1.medium.com/max/10368/0*_j2PiIukj17JYS3w)

Use a ***branch*** to isolate development work without affecting other branches in the repository. Each repository has one default branch, mostly called the `master` branch and can have multiple other branches. It represents an independent line of development. You can think of them as a way to request a brand new working directory.

You can even create a new branch using GitHub.

![Branch selector menu](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059413259/Z9Xg4IFte.png)*Branch selector menu*

*How to create a new branch:*

* *On the main page of the repository, click the **branch selector menu**.*

![Creating a new** branch **named ‘fix-title’](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059415303/aZtd4E4QH.png)*Creating a new** branch **named ‘fix-title’*

* *Type in a new name for your branch then select **Create branch**.*

![Branch created](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059417237/CDypIyRVp.png)*Branch created*

Awesome! Notice that the number of branches increased by one and the branch selector menu now shows that you are on the newly created branch. You now have a new branch.

You can proceed to work on it without affecting the master/main branch.

### 4. Cloning a repository.
> **Cloning** utility which is used to target an existing repository and create a clone, or copy of the target repository.
> - Atlassian.com

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059419135/8ztojmZJ-.png)

Cloning a repository means that you’re downloading a copy of the source code from a specific source.

Right now, you have a fork of the repository you forked, but you don’t have the files in that repository on your computer. 
Let’s create a clone of your fork locally on your computer.

*How to clone a repository:*

* *Click on the green **Clone or Download** button in the forked repository. This will initiate a popup titled ‘Clone with HTTPS’.*

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059421428/xmRv9-lEI.png)

* *Copy the **URL** on the popup manually or by clicking on the copy button shown above.*

* *Open terminal or the command line in any folder on your device.*

* *Type in the command `*git clone*` proceeded by the URL copied from the popup. In my case: `*git clone*`

* `[https://github.com/paulonteri/Website.git`](https://github.com/paulonteri/Website.git)

You should see output that is similar to what is below.

![`git clone`](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059424420/lk8kSc-cu.png) `git clone`

Check out what is in your folder using the `ls` command on a Mac/Linux and `dir` on a Windows device. I also use the `tree` command that can be installed separately. 
An alternative would be to open the folder using your default file manager.

![Folder content using the ‘ls’ and ‘tree’ command](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059426703/jq6jMqjk9.png)*Folder content using the ‘ls’ and ‘tree’ command*

Now that you have the project files, you can freely edit them. 
You can open the files in a text editor of your choice and start working on them.

![Repository content in my text editor.](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059428741/LKTe9CjpL.png)*Repository content in my text editor.*

![Repository content on my GitHub](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059431100/vwh34Pbgu.png)*Repository content on my GitHub*

It’s awesome that you now have the content that was on your GitHub.

### 5. Making the changes.

This is where you now make your changes to the files.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059432872/Dyj-3fDSk.png)

![I changed the HTML website’s title.](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059434764/irShAVHXF.png)*I changed the HTML website’s title.*

![VS Code, a text editor, has a feature that shows you the changes you’ve made.](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059437481/ZuchzYdpz.png)*VS Code, a text editor, has a feature that shows you the changes you’ve made.*

Who doesn’t love VS Code?? 😍😍😍

### 6. Add & Commit the Changes
> The `*git commit*` command will save all staged changes, along with a brief description from the user, in a “commit” to the local repository.
> - guide.freecodecamp.org

![Photo by [Roman Kraft](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059439382/7T61UMLWA.html) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)](https://cdn-images-1.medium.com/max/14720/0*ADZRdvvpTeARozI2)

> The `*git add*` is a command, which adds changes in the working directory to the staging area. With the help of this command, you tell Git that you want to add updates to a certain file in the next commit.
> - w3docs.com

The `git commit` command will save the changes you made.

However, you have to explicitly tell Git which changes you want to include in a commit before running the `git commit` command. This means that **a file won’t be automatically included** in the commit just because it was changed. Instead, you need to use the `git add` command to mark the desired changes for inclusion.

*For Example, these are the steps I took:*

* *I navigated to the project’s folder using terminal(this can also be done using CMD)*

* *I pulled and created locally the specific **branch** I want to commit to using `git pull `which will take two arguments; the local-branch-name:remote-branch-name(GitHub remote name) which should be the same.*
`git pull &lt;local-branch-name&gt;:&lt;remote-branch-name&gt;
`*In my case:
`git pull origin fix-title:fix-title
`I then moved to the specific branch I want to work on using `git checkout`.(The default branch is `master`)
`git checkout fix-title`

![**git pull **& **git checkout**](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059441160/ECgGLmphy.png)

* Then **staged**/added the index.html file using `git add`.
`git add Index.html`

* I then committed the changes using the `**git commit`** command. 
I also added a short description/**message** of the changes made using the option`**-m`** (that stands for ‘message’) followed by my message in quotation marks `**" "`**.
`*git commit -m “Changed the website title”`

![git pull, git checkout, **git add** & **git commit -m “**your message/description**”**](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059443021/muP0zSFPx.png)*git pull, git checkout, **git add** & **git commit -m “**your message/description**”***

### 7. Push the changes.
> The `git push` command is used to upload local repository content to a remote repository. **Pushing** is how you transfer commits from your local repository to a remote repository.
> - Atlassian.com

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059444976/TCIIVNbvOv.jpeg)
> **Note:** 
The `git commit` command captures and saves the project's current changes. However, commit is **not automatically transferred to the remote server**, in this case, GitHub. Using the `git commit` command only saves a new commit object in the local Git repository.

You can use `git push` command to upload the content of the local repository to GitHub.

The `git push` command takes two arguments:

* A **remote** name, for example, `origin` the default remote name is always ‘origin’.

* A **branch** name, for example, `master` or the branch you created.

```
git push * <remote> <branch>*
```


![**git push**](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059447830/PyvD_l5UK.png)***git push***

Carry out the `git push` command and if everything is okay so far, you will be requested for your username and password proceeded by your changes being **pushed** to the** branch you specified **on GitHub.

Your changes will now be visible on GitHub.

![A **new commit** with the** message** you specified.](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059449917/awtMA6Y5q.png)*A **new commit** with the** message** you specified.*

![Visualizing your changes.](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059451828/gE__tBAG2.png)*Visualizing your changes.*

### 8. Make a Pull Request.
> **Pull requests** let you tell others about changes you’ve pushed to a branch in a repository on GitHub.

![Photo by [Christina @ wocintechchat.com](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059453919/rtTnThvWPO.html) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)](https://cdn-images-1.medium.com/max/12032/0*VXdhgLHDcFXgShOT)

**Pull requests** are a feature that makes it easier to collaborate with others. They provide a user-friendly web interface for discussing proposed changes before integrating them.
Once a pull request is opened, you can **discuss and review** the potential changes with collaborators before your changes are **merged** into the official repository.

*How to submit a pull request:*

* *On the repository branch you have worked on, click on the **New pull request** button. This will be somewhere on the left near the branch selector button.
Once clicked, you’ll be taken to a new screen.*

![Click on the **New pull request** button.](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059455722/Te6_xVTym.png)*Click on the **New pull request** button.*

* *On the next screen, use the** base branch** drop-down menu to select the branch you’d like to merge your changes into, then use the compare branch drop-down menu to choose the topic branch you made your changes in.
In my case, the base repository I’m merging to is **oigara/website** and the base branch is **master**.*

* *It’s also nice to give a small, clear and concise **title** and* ***description** of the changes you’ve made.*

* *To create a pull request that is ready for review, click **Create Pull Request**.
 To create a draft pull request, use the drop-down and select **Create Draft Pull Request**, then click **Draft Pull Request**.*

![Give a small title and description for your pull request then click** Create pull request**.](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059457725/U4j_4Bm56.png)*Give a small title and description for your pull request then click** Create pull request**.*

* *You’ve created a pull request. 🔥🔥
The repository’s maintainers will review your contribution. From there, they can merge it if it is good, or they may ask you to make some changes.*

![Pull request Created](https://cdn.hashnode.com/res/hashnode/image/upload/v1625059459696/-0v5Huxgk.png)*Pull request Created*

* *Done. Just wait for feedback.*

## Final Remarks

Additional notes:

* The first draft had over 4000 words! It was too long. I had to cut out some parts and as a result, most parts of this article aren’t fully exhausted and can(should) be separate articles. Try to research more.

* Most of the commands I used here via terminal are accessible via easy to use buttons on most text editors.

* Open Source is a Habit. Nurturing this habit changes your identity as a Developer - *Prosper Otemuyiwa.*

As I finish, I’d like to greatly thank the **Open Source Festival 2020** organisers and the **Open Source Community Africa**. From the great speakers, wonderful keynotes, fantastic breakout sessions and the amazing content they had to offer. I learned a lot.
I actually wrote most part of the first draft of this article on my flight back home from the festival.

### What Next?

1. Learn how to use git on your favourite text editor instead of on the command line.
2. Find **open-source projects** that interest you and try contributing to them as often as possible.
3. Continue loving VS Code.
4. Try out Nigerian Jollof. I first had it this year, 2020, and it was the best!
5. Let’s connect. Let’s talk Open-Source, React, Django and anything software development on [Twitter](https://twitter.com/paulonteri) and [LinkedIn](https://www.linkedin.com/in/paulonteri/).
> This is my **first article**  🙂.
> Please feel free to comment, share the article and offer me some [feedback](https://twitter.com/paulonteri).
> Thanks for your valuable time.
> Goodbye.