# Installation of the open source version of Artifactory.
![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

Connect via `http://<some ip>:8081/artifactory/` using the credentials `admin`/`password`.
After logging into the system, you can opt to import my system configuration.  The
export folder is in the home directory of provisioned machine and is named `artifactory-system-export`.
When you imort the system, you must ensure that ` Exclude Content` and ` Exclude Metadata` have been selected.
Otherwise, the import will fail.

Requirements
------------

TODO

Role Variables
--------------

* artifactory_install: true

Dependencies
------------

* kurron.jdk

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.artifactory }
```

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟