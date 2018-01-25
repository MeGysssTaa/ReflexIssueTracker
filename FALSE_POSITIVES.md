> Make sure to read this article before pushing your issue if you're about to report false positive.
> This will make your and our life easier, and will speed the fix of the issues you report up.



## Introduction

**What are False Positives (FPs)?** A moment when an innocent, 100% legitimate and fair player whose latency and lag status are considered admissible, gets falsely classified by Reflex as a cheater while doing regular, 'daily', actions under regular and stable server performance/TPS, and, henceforth, kicked or banned from the server. Deliberate attempts to provocate Reflex on a 'false positive' by doing abnormal or heavily suspicious actions, playing with irregularly severe lag or attempting to 'look the way a cheater does' is not considered a FP. Reports comprising such behavior are more often closed or ignored without taking care about them.


**This IS a false positive:** a player with an estimate Lag Points (LP) number of 10-35 and a Lag Status (LS) considered 'OK' is fighting against an **active** player, whose LP and LS are respectively equal to 10-35 and 'OK', normally, doing ordinary, common, 'daily' actions and acting the way most legitimate players do, gets a, say, 'coincidence: #325' flag with violations number of 100 or higher, and, hence, gets kicked from the server falsely.


**This IS __NOT__ a false positive:** a player with an estimate LP number of 40 or higher (and, hence, a ping of 300-350 or higher) is getting kicked from the server falsely in/after an active/passive fight against a player, where the now kicked player experienced difficulties because of vivid lag. *Such situations are very unlikely to appear to be fixable because of lack or suspiciousness lagging clients provide. If most players on your server have high latencies, you should actually think of moving your server to the location where most of your players join from. If around or less than 1/3 of your players are facing false positives caused by lag, feel free to disable the problematic checks (however, if there are many, please think of playing with the configuration a bit, and reporting the most common false positives on the Issue Tracker — we **may** ignore them, but we may also **fix** them).*


**This IS __NOT__ a false positive:** a player is fighting a **passive** entity (a player who's AFK or a 9999 HP mob) for a long period of time (over a minute) non-stop. *Reflex is designed to work in the established and common situations and, mainly, for real PvP. Continuous fights against passive entities may sometimes result in sufficiently difficult but useless to fix false positives.*




## How to report a false positive

First off, please remember once and forever: a "I have fp please halp!" message will never be considered a **valid bug report**. Neither on the Reflex issue tracker or on the other project' one. Moreover, before repoting a false positive, make sure that it is actually a **false positive**! There are, sadly, cheaters who are mad of the anticheat detecting their clients and, hence, attempting to persuade server owners they are getting false positives. 


The false positive report should include, at least, a video-evidence clearly demonstrating not less than the last 5 seconds of the fight before kick, and the relevant Reflex logs, either in a form of in-game verbose which can be easily seen on the video, or, even better, an attached Reflex log (if you want your issue to be easier for us to understand, make sure to only include log entries that contain information relevant to the false positive you are reporting — to the one shown in the video).


Secondly, the video should be uploaded as a **video** and **__NOT__ as a GIF**, should be at least 30 FPS and should have a quality of at least 480p.


**Finally**, if you are experiencing many various false positives, make sure to **report them all**, and not only a single one. 


## False positives classification

Reflex has many various checks, and, therefore, some of them need require different approachs.

Here is a simple map of the most frequently reported false positives to the descriptions of their processes of resolving.


**KillAura // 'coincidence: #...'**. This is a **machine learning** detection result. The simplest way to get it fixed is to simply contact us directly. We will then hire you to join the testing server to fix your false positive, if we can't reproduce it ourselves.


**KillAura // 'front entity'**. If you have tons of false 'front entity' flags, then something is simply wrong with your server world. You can easily resolve this yourself: just turn the `killaura.realistic_entityids` settings in the configuration **off**.


**BlockActions // 'bs: ...'**. It appears that you are building too quickly. If it happens that you are getting many false flags when performing unusual bridging techniques, e.g. 'moonwalk' or 'breezely', simply reduce the `blockactions.min_bridge_delay` number in the config to be a little bit lower than the values you get in verbose. So, say, if you're facing false positives saying 'bs: 272' or 'bs: 260', you should set the `min_bridge_delay` option to `250`.




If you want this article to be more helpful, be somehow improved or extended, don't hesitate to contact us and we will listen to your suggestions!
