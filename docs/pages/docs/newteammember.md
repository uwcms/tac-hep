---
permalink: /docs/newteammember.html
layout: default
title: Information for new TAC-HEP team members
pagetype: doc
---
#### TAC-HEP website

* Add a photo named `First-Last.jpg` or `.png` to the [assets/images/team folder][]. It should be 320x240 pixels.
* Add a "`<your github username>.yml`" file to the [people folder in the website repository][people]. Here is an example:

```yml
active: true
focus-area:
- <primary focus area(s), a list>
institution: <Your University>
name: <Your name>
photo: /assets/images/team/<First name>-<Last name>.jpg
shortname: <Your GitHub user ID>
title: <Can be blank - will show a title under your picture>
website: <Optional, your website>
presentations:
  - title: How to make green eggs and ham
    date: 2018-09-10
    url: https://indico.cern.ch/event/697389/contributions/3062046/attachments/1712602/2761531/ROOT2018-Union.pdf
    meeting: ROOT 2018 Users Workshop
    meetingurl: https://cern.ch/root2018
    project: greeneggs
    focus-area: as
    location: Virtual
```

* Add your GitHub username to the proper [university file][]. Note that you will *not* show up in the full team page if you are not in a university file!

