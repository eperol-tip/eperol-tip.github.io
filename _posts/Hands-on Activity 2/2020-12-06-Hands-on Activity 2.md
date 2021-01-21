---
layout: post
title:  "Hands-on Activity 2"
date:   2020-12-06 11:59:00 +0700
categories: Hands-0n Actitviy
---
Follow procedure:

    Create an account in Github.

Username should be your given initials and last name followed by -tip (e.g. ajcanlas-tip)

Use your TIP email address for this (if you have already linked your email with GitHub create a separate one)

Verify your account in your email in GitHub,

    Create a repository with your username (in my case it is ajcanlas-tip) without any files, and it should be public.

    In your Alpine VM clone the repository you just created in my case this is my url (https://github.com/ajcanlas-tip/ajcanlas-tip.git (Links to an external site.))

    Create a profile with Markdown this is a cheat sheat (Links to an external site.) in a "README.md" file

README.md should have the following:

    Your full name

    Year Level

    Interests

    email address

    Computer specs (CPU/Ram size/Disk type and size)

    To add it to your profile add the README.md file commit it then push it in the repository (to push a repository use git push -u origin master)

Commands:

git add README.md

git commit -m "First commit"

git push -u origin master

    Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git (Links to an external site.)

    Clone your newly forked repository with git clone h (Links to an external site.)ttps://github.com/< your username >/sysad2-12021.git and go in the repository directory.

    Make a new branch named "activity2" using git branch activity2 and git checkout activity2


    Make a new new remote upstream with git

    Create your directory with your username, create a directory named "activity2" add the previous README.md file as HA2.md

Command used:

    mkdir

    mkdir activity2

    cp HA2.md

    add,commit and push it to your activity2 branch

Commands used:

    git add HA2.md

    git commit -s -n "activity2"

    git push -u origin upstream

12.Request a pull request for the master branch in https://github.com/ajcanlas-tip/sysad2-12021.git (Links to an external site.) and activity2 branch of your forked repository

OUTPUT: https://github.com/eperol-tip/sysad2-12021/blob/activity2/eperol-tip/activity2/HA2.md

{% highlight ruby %}
.  
├── HA2.md  
└── README.md  

{% endhighlight %}