---
layout: post
title:  "Hands-on Activity 5"
date:   2020-12-13 11:59:00 +0700
categories: Hands-0n Actitviy
---
Procedure:

1. Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git

2. Clone your newly forked repository. 

3. Make a new branch named "activity5" from master branch using git branch activity5 and git checkout activity5

Note: To Prevent Conflicts Create a directory with your username as its name and go inside of it, and create a directory called "activity5" and go inside it.

4. Make a new new remote upstream with git remote add upstream https://github.com/ajcanlas-tip/sysad2-12021.git

5. Optimize the playbook in Hands-on Activity 4: Ansible Playbooks

7. add,commit and push it to your activity5 branch

8. Request a pull request for the master branch in https://github.com/ajcanlas-tip/sysad2-12021.git  and activity5 branch of your forked repository.

Output: [On GitHub](https://github.com/eperol-tip/sysad2-12021/commit/1b34689c5e01cd936d38cb4505a5fc36f265e03f)

{% highlight ruby %}
.  
├── act5
├── playbook.yaml  
├── ansible.cfg    
└── roles  
    ├── install_centos  
    │   ├── README.md  
    │   ├── defaults  
    │   │   └── main.yml  
    │   ├── handlers  
    │   │   └── main.yml  
    │   ├── meta  
    │   │   └── main.yml  
    │   ├── tasks  
    │   │   └── main.yml  
    │   ├── tests  
    │   │   ├── inventory  
    │   │   └── test.yml  
    │   └── vars  
    │       └── main.yml  
    └── install_ubuntu  
        ├── README.md  
        ├── defaults  
        │   └── main.yml  
        ├── handlers  
        │   └── main.yml  
        ├── meta  
        │   └── main.yml  
        ├── tasks  
        │   └── main.yml  
        ├── tests  
        │   ├── inventory  
        │   └── test.yml  
        └── vars  
            └── main.yml  

{% endhighlight %}