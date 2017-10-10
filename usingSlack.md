| [Previous: Using GitHub](usingGithub.md) | [Main Page](README.md) | [Next: Creating GitHub Content](creatingGithub.md) |
|--------------------------------|-----------------------------|------------------------|

# 3. Using Slack for Class Communication

Many LMS systems provide group and private chat options now, and our students certainly don't lack for real-time communication tools to talk to us and each other. So why add another tool to the mix? And why Slack in particular?

- RIT is a co-op education school, which means our students go out on semester-long work experiences several times during their degree. Many of them will end up at companies using Slack, so this gives them hands-on experience with an important productivity tool.
- Slack has excellent mobile clients, which is typically the very best way to reach my students. (As we all know, email is pretty low on the list of ways to get your students' attention quickly.)
- Slack's integrations, especially with Google Docs, GitHub, and Trello, are extremely useful in my classes, where those services are also an important part of the instructional technology used. 
- Slack makes it easy for students to upload the files they want me to look at, and displays/formats code snippets as well
- I can easily create private group chat channels for student groups, and be a member of those channels, which helps greatly in assessing ongoing participation and group dynamics issues
- It's easy for me to add external people to a Slack workspace, which comes in handy when I've got a class working on a project with outside experts. 

One of the biggest drawbacks of using any type of real-time messaging with active groups, of course, is that it can turn into a major source of productivity-killing interruptions. That's why for years I've avoided using it for most work-related activities. However, when I use it with students, it allows me prioritize their questions over the mountains of less important (but still non-spam) email I get every day. To keep that under control, however, the *only* Slack workspaces I check regularly are the ones for my currently active classe--and once the term is over, I stop checking the workspaces entirely. (I'll still respond to former students' questions, of course, but they do lose their "priority access" to me. ) 

Getting students (or any group!) to adopt new communication tools can be a challenge, and the first time I tried using Slack in the classroom it wasn't as successful as I'd hoped. Since then, I've started doing a number of things to increase its use my students. 

For privacy reasons, I can't give you a live tour of my class workspaces, but I've created anonymized screenshots to illustrate some of my approaches.

### Preventing Notification Spam
One of the biggest problems with having students (or anyone else) adopt a new chat tool is the risk that they'll have to deal with too much unwanted/unnecessary chatter. But if students don't install the mobile client and turn on notifications, they'll lose much of the value of the tool. 

To address that problem, I renamed the \#general channel (which all new users are automatically subscribed to by default) to \#announcements, and set it so that only my TAs and I can post to it. I use that channel to let them know about useful things, like upcoming deadlines, extensions on due dates, and why I might be a few minutes late for class; that gives them a good reason to set up the mobile client and enable notifications. Because nobody but the TAs and I can post there, they don't mind keeping notifications turned on for that channel. 

![Class announcements channel](images/slack-classroom-announcements.png)

I also walk them through how to change notifications for the workspace, so that they don't get constant notifications from channels that are lower priority. 

### Inviting Information Engagement
In each class workspace, I create at least one non-classwork channel that invites playful participation--this semester I created a music suggestions channel where they can post songs they'd like me to add to the class playlist (which I play on in the background when they're working on in-class exercises).

![Slack music suggestions](images/slack-classroom-music.png)

### Requiring an Introduction
To nudge students into setting up an account and using it to post content, I assign an exercise at the start of the term that requires them to post to the \#introductions channel, so I can be sure they've set up an account and figured out how to join a channel. In my web class, I also use this as a way to collect their GitHub usernames, which I will need later in the term. 

![Slack intros](images/slack-classroom-intros.png)

### Slack-Only Opportunities
I tell students that they're welcome to continue using email to contact for me for course related issues, and that after the initial introduction exercise is done they can choose not to check Slack again. However, I also do offer some "bonus" opportunities for those who do use Slack--for instance, when I recently offered my web design students the opportunity to resubmit a project for an improved grade, I told them that they needed to contact me via Slack (and include a link) to request that I regrade their revision.

### Easy Access to Slack (and GitHub) from LMS
Our LMS (Brightspace, formerly D2L, allows customization of the navigation bar for a class. I added custom links to both the GitHub repo and the Slack workspace from that, as well as adding a prominent "news" item on the first page with links to both. 

![Slack links in LMS](images/slack-lms-link.png)

### Committment to Quick Responses
Most importantly, I've committed to responding quickly to student messages. I have the Slack client on my phone's home screen, and I check for new notifications at least twice a day. If a message can be answered quickly, I do it then. If not, I acknowledge it, let them know I'll get back to them, and mark it with a star for later access. When I have a little more time, I go through my starred messages and respond in more depth. 

(The example below also shows how easy it is for them to share code with me in their messages.)

![Slack response](images/slack-snippet.png)

## Slack vs Email
I have not stopped using email for communicating with students, of course. Anything that I might need a "paper trail" on--warnings about grades, requests to meet with them in my office hours, etc--still gets sent by email. And there are definitely students who prefer using a familiar mode of communication to contact me. 

Ideally, though, I want my students to see Slack as an easy and non-threatening environment to ask questions, make comments, and get help. I tell them (and it's true) that it allows me to prioritize their messages over the piles of email that I get on a daily basis. And I've found that once I get them over the adoption hump, most of them appreciate Slack's informality and ephemerality. Most importantly, I hear from far more students who have questions or concerns than I did in the past. 

| [Previous: Using GitHub](usingGithub.md) | [Main Page](README.md) | [Next: Creating GitHub Content](creatingGithub.md) |
|--------------------------------|-----------------------------|------------------------|

| [Main Page](README.md) | [Next: Using GitHub for Course Materials](usingGithub.md) |
|--------------------------------|-----------------------------------------------------|
# 1. Introduction: Understanding GitHub and Slack

Let's start with the basics of what GitHub and Slack are, and what they're used for.

## GitHub
[GitHub](https://github.com/) is a site where anyone can store a repository (often referred to as a "repo") of documents. While it is most often used to store, share, and collaborate on source code for software projects, repos can include any type of digital file--including human-readable documentation pages like this one!

### GitHub vs git
GitHub gets its name from the software it uses to keep track of files and changes, which is called git. Git is what's known as version control (or source control) software, and developers use it to keep track of changes that they and others make to files. 

You can run git on nearly any type of computer--Windows, Mac, Linux, etc--and it's a standard tool for most software developers these days. Git is considered *distributed* version control, which means that each person working with the repository of documents has their own complete copy of the files, which they can sync with any other copy of the repository. Typically, one copy of the repository is placed on a server accessible to all developers, and designated as the primary shared version. Developers modifying the code on their own machines then send their revisions to the copy on the server. 

GitHub is simply a publicly accessible shared server running git, with a web-based interface, which can be used to host both public and private repositories of digital files. Many open source projects are housed on GitHub, allowing anyone to download the most recent version of the software, as well as permitting them to assist with improving the code (don't worry, there are controls over that process!). GitHub isn't the only server offering this functionality, but it's well known and widely used, so it's the one we'll be working with today. 

### Learning git
In today's workshop, we're only going to work with the web-based interface to GitHub, so you won't need to have git installed on your own computer. However, if you end up deciding to regularly publish content on GitHub, it will be important to learn how the underlying git software works, and how to use it on your own computer. My favorite tutorial for this is a James Williamson's [GitHub for Web Designers](https://www.lynda.com/GitHub-tutorials/GitHub-Web-Designers/162276-2.html) tutorial on Lynda.com--unfortunately, it requires a subscription, and could use a litle updating since it was published three years ago. There are also many other tutorials and guides for both git and GitHub available online. 

### Creating a GitHub Account
Before we go any further, make sure you've created a free GitHub account (if you don't already have one). You can do that by clicking the "Sign Up" link in the top right corner of this page! (If you already have an account, there's no need to create a new one--just sign in with that.) 

## Slack

At its core, Slack is a group messaging tool. It provides a group workspace with both public and private channels for discussion, private messaging capability, and file storage. Once you've created a Slack workspace, it can be accessed using either a web interface or one of their many clients for desktop and mobile devices.

There's a lot more to Slack than than text messaging, though, which is one of the reasons it has become so popular in business settings. (That's also why, even in the ["What is Slack?"](https://get.slack.help/hc/en-us/articles/115004071768-What-is-Slack-) portion of their Getting Started guide, the description is pretty vague!) One of Slack's most powerful features is that it can be extended with a wide variety of apps that integrate it with other online services--from Google Docs and Dropbox to Trello and even GitHub. 

### Joining the Workshop Slack
The best way to understand how Slack works is to actually play around with it, so I've created a workspace for this workshop. I've set it up so that anyone with an @rit.edu address can join it. https://ritworkshop-oct17.slack.com/messages  

>**Note**: If you already use Slack with another group or project, be aware that every Slack workspace is a completely separate instantiation--a login on one Slack workspace can't be used on any other workspace. This can also be confusing for students who are already using Slack for other purposes. You can be logged into different workspaces in different tabs on the same browser, though, and all of the Slack clients allow you to be logged into multiple workspaces. 

Slack workspaces can also be set up with a generic invitation link for joining; those invitations expire after a set date. And/or you can generate individual invitations to specific email addresses. 

Here's what my Mac desktop client looks like when I'm logged into the workspaces for both of my current classes and the one for this workspace:

![Slack Workspace Screenshot](images/slack-workspace.png)

I've done only a small amount of customization on this workspace. Click on the  **Channels** heading (the word itself, not the plus sign), to see a list of available channels in the workspace. In addition to the two channels (\#general and \#random) that are created by default in a new workspace, there should be three additional channels visible to you: \#introductions, \#github, and \#music-suggestions. Go ahead and join the \#introductions channel, and post a brief intro there. 

After you've posted your intro, take a look at the \#github channel. This is an example of a Slack integration. I've set it up so that every time I send changes to the GitHub repo for the workshop, that information is automatically posted to this channel. In my classes, this lets students see if and when I've made changes to the syllabus or assignments--and what the short description of those changes are. 

You may also want to customize your notification settings for this Slack so you don't get overwhelmed with messages (that's particularly important if you're using a mobile client). 

![Slack notification settings](images/slack-notification-settings.png
)

Feel free to use the \#general channel to chat about the session as we go along. (Full disclosure: I won't stay logged into this workspace after the workshop is over, so while you can continue to chat with other participants, you won't be able to ask me questions there. Feel free to email me, though!)

| [Main Page](README.md) | [Next: Using GitHub for Course Materials](usingGithub.md) |
|--------------------------------|-----------------------------------------------------|

***This page is part of Liz Lawley's "RIT Teachers on Teaching" workshop, 11 October 2017***