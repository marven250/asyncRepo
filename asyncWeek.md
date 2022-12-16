# How to Approach Async Week:

Below are the topics to complete before Senior phase starts!

A few notes:

- It's best if you do the mandatory workshops _In order_. Each will build upon concepts
in the the previous topic.
- Our Project Boilerplate includes a playlist of videos to review ahead of Sr Phase: Testing, Deployment, and Security There are timestamps for each topic in the video description.

| Topic       | Priority   | Lecture        | Workshop/Lab        | Solution     | Review      |
| ----------- | ---------- | -------------- | ------------------- | ------------ | ----------- |
| Boilermaker | **Mandatory** | - | [🖼️ Exercise: Boilermaker][workshop_boilermaker] | [👾 Boilermaker][solution_boilermaker] | [📺- Security][security-playlist] [📺- Testing][Intro to testing playlist] [📺- Deployment][heroku-video] |
| Async Week Project | **Mandatory** | - | (see details below) | - | - |
| Heroku Deployment| **Mandatory** | (lecture in workshop) | [🖼️ Exercise: Deployment][workshop_deployment]   | - | - |
| React Hooks | Optional | [📺][hooks-lecture] | [🖼️ Hooks Documentation][hooks-docs]<br/>[🖼️ React Checkpoint (start over with hooks)][react-cp] | - | - |
| Security Readings | Optional | - | (see links below) | - | - |

[hooks-lecture]: https://youtu.be/e18Kuwn0GR0
[hooks-docs]: https://reactjs.org/docs/hooks-overview.html
[react-cp]: https://github.com/FullstackAcademy/checkpoint-react-v2
[workshop_boilermaker]: https://learn.fullstackacademy.com/workshop/589f3d5b12f93c00045c27fd/landing
[solution_boilermaker]: https://github.com/FullstackAcademy/fs-app-template
[boilermaker_review]: https://www.youtube.com/playlist?list=PLx0iOsdUOUmn7D5XL4mRUftn8hvAJGs8H
[workshop_deployment]: https://learn.fullstackacademy.com/workshop/5bad3ec1ecb5e7000452b2d6/landing
[Intro to testing playlist]: https://www.youtube.com/playlist?list=PL_yPiP-ZZLhIA7zPzYMTSQOnmQevX2Ivt
[security-playlist]: https://www.youtube.com/playlist?list=PL_yPiP-ZZLhJfnvYtJGkzJObGHKdINpQF
[heroku-video]: https://www.youtube.com/watch?v=Iz23rO7LvbE

## 🔎 **Async Week Project** 💡

### **What?**
Absolutely anything you want it to be. This is meant to be “_fun and playful_.” If what you deliver is incomplete, **that’s fine**! Think of this as a very low-stakes sandbox.

For some inspiration, check out this [list of technologies](https://docs.google.com/spreadsheets/d/1aApC_9G1tG1q3LfCfliUPHrK7NF2d3K9_Wu4mPT9BpY/edit?usp=sharing) to explore.

### **When?**
It is **due by Friday at 1pm (EST) of Async Week**.

### **How?**
Record a **short** (`<= 5` minutes) screencast and upload to YouTube as an **unlisted** video.

Your video submission does ***not*** have to be polished. **At all.** You’re ***not*** expected to show this to anyone outside of this class. Just think of it as a casual class presentation. Keep it conversational.

On the due date, an instructor will start a thread within the cohort Slack channel.

Share the name of the technology you used, a quick description of what the technology is used for, and the link to your YouTube screencast.
- For example, Slack, "***D3.js - JavaScript library for producing dynamic, interactive data visualizations in web browsers. [insert link here]***," which can foster a conversation amongst each other like so:
  - “Wow I didn’t know you could do that with D3!”
  - “Thanks, I really liked your Neo4J demonstration. How’d you get that graph to show up?”

### **Why?**
**To explore and have fun!** Seriously. This is an opportunity to goof off with **new technology** _without_ any specific expectations. You don’t have any requirements to fulfill or tests to pass. If your project is unfinished and totally broken, that’s **perfectly okay**. Just talk about what you learned.

**<details><summary>FAQ</summary>**

- ***Will the help desk be open?***
  - No, during Async Week the help desk is _not_ open.
- ***What if nothing works?!***
  - It's OK! No stress. In your video, just share things like _why you picked the technology_, _what challenges arose_, _what you learned from the experience_, etc.
- ***Can I reach out to anyone if I have a general question?***
  - Absolutely! Throw your question in the **cohort Slack channel** and the instructor(s) will respond when they can!

</details>

#### Security resources:

##### Overview

Take a look at [OWASP’s top 10][owasp-top] and for a different perspective
[this article][common-vulnerabilities] for some reading about common web
security vulnerabilities.

[owasp-top]: https://www.owasp.org/index.php/Top_10_2013-Top_10
[common-vulnerabilities]: https://www.toptal.com/security/10-most-common-web-security-vulnerabilities

##### Details

- Look into these vulnerabilities more in depth

  - [Injection](https://owasp.org/www-project-top-ten/OWASP_Top_Ten_2017/Top_10-2017_A1-Injection)
  - [Poor Authentication][poor-auth]
  - [Cross-Site Scripting][xss]
  - [Data Exposure][data-exposure]
  - [Missing Access Control][missing-access-control]
  - [Cross-Site Request Forgery][csrf]

- Check out these articles on

  - [What HTTPS is/does][https-intro]
  - [Public-key cryptography][public-key-crypto]

[poor-auth]: https://owasp.org/www-project-top-ten/OWASP_Top_Ten_2017/Top_10-2017_A2-Broken_Authentication
[data-exposure]: https://owasp.org/www-project-top-ten/OWASP_Top_Ten_2017/Top_10-2017_A3-Sensitive_Data_Exposure
[xss]: https://owasp.org/www-project-top-ten/OWASP_Top_Ten_2017/Top_10-2017_A7-Cross-Site_Scripting_(XSS)
[csrf]: https://owasp.org/www-community/attacks/csrf
[missing-access-control]: https://owasp.org/www-project-top-ten/OWASP_Top_Ten_2017/Top_10-2017_A5-Broken_Access_Control
[https-intro]: http://robertheaton.com/2014/03/27/how-does-https-actually-work/
[public-key-crypto]: https://blog.vrypan.net/2013/08/28/public-key-cryptography-for-non-geeks/

Feel free to read as much as you can, but there is a lot to cover so don't
worry if you cannot get through it all.
