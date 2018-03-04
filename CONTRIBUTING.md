## Welcome here!
### This article will guide you through this issue tracker and will teach you how to report an issue, suggest a feature or ask a question  easily and efficiently. Moreover, this article is **required** to read before posting your first issue.




## General
When creating a new issue, a pre-filled text field can be noticed. Please do not erase anything in it unless you are asking a very simple question or suggesting a very simple and small feature.


## Filling the template
### Introduction
Let's start filling everything.


All the data should be written near the "＞" symbol. 
First off, you need to know what are you reporting. That is either a **BYPASS** (if you can hack without getting detected), a **FALSE POSITIVE** (if you're getting kicked for hacking while playing legitimately), a **CONSOLE ERROR** (Reflex-related errors (stacktraces) in your server console), a **BUG** (some other form of unexpected plugin behavior), a **QUESTION** (Reflex-related question which has no answer in the FAQ of the plugin) or a **FEATURE REQUEST** (if you want us to add or change something in Reflex). 

Write your issue type near the "＞" symbol under "ISSUE TYPE" title like here:
![sc001](https://pp.userapi.com/c840537/v840537498/29af9/pFR-uSFgKIs.jpg)




### Bug report basics
If your issue is of type **QUESTION** or **FEATURE REQUEST**, erase the "Unexpected plugin behavior report" title and everything written under it and skip to the "Before submitting" article. Otherwise, you shall fill four fields of this section:


**（１）Debug.** Reflex has an awesome debugging feature in it which collects all the relevant server and plugin information and writes it to a file. Type `/reflex debug` in-game or in your server console. Reflex will give you a link which you need to copy and paste in the "Debug" field.


**（２）Dump.** Type `/reflex dump` in-game or in your server console and wait some seconds until a message that shows everything's finished appears. Then go to your Reflex folder ("/.../plugins/Reflex" by default) and look for a recently created "dump-..." file. Open it using any text editor, copy everything and paste on [p.reflex.rip](https://p.reflex.rip). Put the link of your paste in the "Dump" field.


**（３）Server log.** Go to your server logs folder ("/.../logs") and look for the "latest.log" file. Open it using any text editor, copy everything (or only the part with the stacktrace (error) if your issue type is **CONSOLE ERROR**) and paste on [p.reflex.rip](https://p.reflex.rip). Put the link of your paste in the "Server log" field.


**（４）Reflex log.** Go to your Reflex logs folder ("/.../plugins/Reflex/logs" by default) and look for the log with the current date. Open it using any text editor, copy everything and paste on [p.reflex.rip](https://p.reflex.rip). Put the link of your paste in the "Reflex log" field.


In the end, the "Unexpected plugin behavior report" section should look similar to this:
![sc002](https://pp.userapi.com/c840537/v840537498/29b4e/d5KTTXEEw_U.jpg)




### Misdetection report
If your bug is of type **BUG**, erase everything written under "Misdetection report" and write the description of your bug there, desirable with video- or image- evidence, and skip to the "Before submitting" article.

Under "misdetection report" we mean that you want to report a situation where Reflex has made a mistake differentiating a hacker from a legitimate player, and therefore both kicked someone legit (**FALSE POSITIVE**) or ignored someone who was obviously cheating (**BYPASS**).


Under **false positive** we mean that a player is 100% legit — that is playing with vanilla/optifine client, not using **any** mods, add-ons, autoclickers, macroses or anything similar since the moment he joined the server, has been doing normal ('daily') actions such as fighting against other players or vanilla mobs, building a bridge to connect the world or walking around the map as usual. If a player is **purposely** trying to look like a hacker (to provocate a "false positive") or doing something extremely unusual or abnormal, then this is **not** a false positive.


Under **bypass** we mean that a player is **blatantly** hacking, dominating over others or gaining himself obviously unfair advantage by acting the way legitimate players can't or by automatizing his actions in the way that is significantly different to normal players' actions for a long period of time without getting detected.


If reporting a **false positive**, make sure to **[READ THIS ARTICLE](https://goo.gl/R93HQy)**!.


If your issue matches these two terms, then let's begin filling the "Misdetection report" template.




In "DESCRIPTION" fields, please point the way you reproduce the false positive you report (i.e. how fast do you need to click and how do you need to move, in what kind of environment do you need to do that, etc.) if your issue type is **FALSE POSITIVE** or the name of hacked client you use and it's settings/configuration you use to avoid getting detected by Reflex if your issue type is **BYPASS**. **WARNING:** DO NOT INCLUDE ANY DOWNLOAD/PURCHASE LINKS, ESPECIALLY IF THE SOFTWARE USED IS PAID.


Now you should record a video-evidence that demonstrates your issue. This is how you do that:

**（１）** Begin recording.

**（２）** Demonstrate that you have no bypass permissions (for instance, type "/op", "/deop" or "/reflex bypass `<YOUR USERNAME>` `<CHECK NAME>` false").

**（３）** Enable in-game verbose by typing **/reflex verbose** (requires **reflex.verbose** and **reflex.command.verbose**).

**（４）** Demonstrate the issue itself. If you are reporting a bypass, your video should last for at least one minute and should demonstrate the advantage you get over legitimate players clearly.




As additional info, you can specify other relevant things which you believe can help us dealing with your issue faster. For example, mouse sensitivity, your activity/free hours when you can cooperate with us, etc.

![sc003](https://pp.userapi.com/c840537/v840537845/299b5/40RJYbp4-PY.jpg)




### Before submitting
Before clicking "**Submit**", make sure that no one has reported any similar issues or asked any similar questions recently. Duplicate issues are ignored or closed without any response, so searching for anything relevant your topic will save your and our time.

**English** is the only language allowed on this issue tracker. Issues in other languages are closed or ignored. You can get support on other languages in [our Discord](https://discord.gg/SdXY6pG). Please make sure that you have filled everything correctly and accurately, and that your spelling and grammar reach the level where we can understand you. If you don't speak English properly, we can't support you properly either.



### Useful information
If your issue has received an "Invalid" label, or if one of Reflex contributors has asked you for additional information, please reply as soon as possible. Issues labeled "Invalid" which haven't been edited or completed by reporter's comment and which exist for over **72 hours** will be closed.

The Reflex Issue Tracker is the only place where you should report bugs. In case you will try to report an issue in our Discord or on Spigot, you will be redirected here.



If you have any more questions, if you believe some useful information might missing in this guide, or if you have found any critical grammar or logic issues, don't hesitate to contact us!
