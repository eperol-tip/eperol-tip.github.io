---
layout: post
title:  "Prelim: Hands-on Activity 4"
date:   2020-12-13 11:59:00 +0700
categories: Prelims
---
Procedure:

1. Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git

2. Clone your newly forked repository. 

3. Make a new branch named "activity4" from master branch using git branch activity4 and git checkout activity4

Note: To Prevent Conflicts Create a directory with your username as its name and go inside of it, and create a directory called "activity4" and go inside it.

4. Make a new remote upstream with git remote add upstream https://github.com/ajcanlas-tip/sysad2-12021.git

5. Create a playbook that install java via package manager , and install boto,ansible,and openstack py packages using pip in both Ubuntu and Centos.

7. add,commit and push it to your activity4 branch

8. Request a pull request for the master branch in https://github.com/ajcanlas-tip/sysad2-12021.git  and activity4 branch of your forked repository.

Output: [On GitHub](https://github.com/eperol-tip/sysad2-12021/commit/a9a35ef5de8021ad4f07a178c3d74fd060e21d1f)

{% highlight ruby %}
.  
├── act4inventory
├── act4playbook.yaml
└── ansible.cfg

{% endhighlight %}