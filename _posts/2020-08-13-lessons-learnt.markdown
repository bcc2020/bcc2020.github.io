---
layout: post
title: "Lessons learnt from organizing a virtual conference (BCC2020)"
date: 2020-08-13 00:00:00
isStaticPost: true
image: conference.jpg
---

Going to a conference - don’t you love it? It might take you to an interesting place to visit, allow you to meet colleagues of old, establish new connections and spontaneously run into relevant conversations. Being away from home and work enables full immersion into the conference programme, with the expectation that you are unavailable for anything else. You are sure to return home brimming with new ideas and connections.

This was the scenario we had in mind for attendees of BCC2020, the first Bioinformatics Community Conference, to be held in Toronto, July 17-24. It was the second time BOSC and GCC joined forces; the first was GCCBOSC 2018 in Portland.

Preparations for BCC2020 in Toronto were starting to ramp up early in the year. Then COVID-19 struck, and everything changed. On March 19th the decision was made to go virtual.

This article provides an overview of how we used Remo and Discord to run BCC2020 online, in the hope that other organisers of virtual conferences can learn from us. We do not cover other aspects of conference organization that are shared with in-person meetings, such as registration, recruiting keynote speakers, abstract selection, promotion, code of conduct enforcement, or schedule creation.

#### Choices of technology

In order to go virtual, we decided that we would need solutions for several problems:

* be able to convey scientific content through keynotes, talks and posters
* allow interactive sessions for training
* allow participants to ask questions of presenters, and presenters to respond
* capture the social aspect of a conference despite being in very different time zones
* have active communication channels to reach all participants with timely updates and allow them to chat with each other

For Q&A and chats, [Discord](https://discord.com/) won out over Slack because it is open source and developer friendly, and also because it does not have a maximum message limit. Discord allows asynchronous communication in multiple topical channels and also permits integration of ‘bots’ to automatically post updates (for example, listing the talks in the next session).

For communication and scheduling, we used a combination of [our website](http://bcc2020.github.io/), [Sched](https://bcc2020.sched.com/), and an “Info-Hub” Google doc that could be updated on the fly.

For presenting content, we considered a mix of breakout rooms and webinars in Zoom for talks, training and BoFs, but no good solution for poster sessions was in sight. After stumbling upon a new virtual platform (demoed on June 18th), we decided fairly last-minute to take a gamble and switch to [Remo.co](https://remo.co/) (June 25th). Most of this article focuses on our experiences with Remo. Before reading on you might want to check out [a short video about our Remo setup](https://youtu.be/HczksYMD-z8) that we provided as starting material for attendees.

&nbsp;

<div style="border:1px; border-color:black; border-margin:10px;">
<img src="../img/posts/whole-room.png" alt="Remo conference room setup, table view" width="100%"/>

<b>Figure 1</b>: Example of Table (or Discussion) view in Remo. Every table represents a separate virtual space in which participants who occupy one of the seats can chat with each other. Webcam windows are shown as thumbnails as in our example or tiled across the whole screen. The coloured, clickable buttons designate connections (or bridges) to other Remo event spaces, or to online resources, such as the Code of Conduct or the conference info hub.
</div>


#### Why did we choose Remo?

Some of the key features in Remo that persuaded us to use it for our online conference are:

* virtual buildings with tables that mimic conference venues and allow attendees to mingle
* seamless switching between webinar-style and breakout rooms (see Figures 1 and 2)
* “bridges” allowed participants to easily jump between parallel tracks
* an intuitive option for posters: presenters are assigned a table with a digital whiteboard on which they can display material including PDFs, videos, links, etc.
* ability to link online resources, such as info docs, video tutorials and the CoC to the virtual space
* sensible default settings that ease admin work regarding access policies and control of sessions

&nbsp;

<div style="border:1px; border-color:black; border-margin:10px;">
<img src="../img/posts/side-by-side.png" alt="Nomi Harris thanks the Org Committee in Remo" width="100%"/>

<b>Figure 2</b>: Example of Presentation view in Remo. This mode can be compared to a webinar style session, where up to six presenters can share their webcam and screen with the audience. By default all windows are tiled and have the same size, but individual windows can be increased to full-screen size.
</div>

&nbsp;

&nbsp;


Some aspects that didn’t work so well in Remo:

* the Chat and Q&A features are quite basic, hence the need for Discord
* you can only have about eight participants’ videos in view at the same time
* presentations can be viewed in either full screen, thereby covering chat and presenter videos, or smaller, equally sized panels, making it hard to see details
* Remo does not currently allow phone-in connections
* Remo does not have a built-in option for virtual backgrounds (to allow participants to turn on their video camera without revealing their room)
* Remo’s permission settings are not very flexible. There are few options between participant and event manager (who can change anything).

#### The Remo Experience

Judging by the feedback that was collected after the conference, the overall reaction to Remo was extremely positive - 40% even said that it was the best aspect of the conference. Very few had experienced the platform beforehand, so it was a learning curve for most, but did not seem to challenge most participants.

Even though we could not transport participants to Toronto, Remo felt a bit like entering a conference venue. The table view allowed attendees to move around and mingle before and after sessions as well as during breaks. It provided opportunities to bump into old friends, make new acquaintances and suddenly find yourself in conversations relevant to your areas of interest. The birds-eye view of the tables and their occupants allowed one to actively seek out busy tables, similar to wandering through a real venue during coffee breaks. It is possible that this social aspect provided by Remo led to the high retention rate: throughout the three days of talks the number of attendees dropped off only slightly.

&nbsp;

<div style="border:1px; border-color:black; border-margin:10px;">
<img src="../img/posts/best-parts.png" alt="Exit survey results about best parts of BCC2020" width="100%"/>

<b>Figure 3</b>: Exit survey opinion on the best parts of BCC. 40% of respondents said that Remo was the best part.</div>

#### Pre-recorded talks, live Q&A, and asynchronous discussion

Except for keynotes, we decided to go with pre-recorded talks, which we streamed within Remo from Vimeo. Live talks were too risky given the vagaries of internet service in many areas (in fact, one of our live keynote talks was interrupted due to an issue in the speaker’s building). Showing pre-recorded talks gave attendees full control as they watched: they could change the volume, turn on subtitles and even pause and skip sections. These videos were also linked on Sched](https://bcc2020.sched.com/), enabling attendees who missed any of the talks to watch them later at their convenience. In fact, those who wanted to could watch the talks in both parallel tracks, which would be impossible at an in-person meeting.

The conference schedule included live Q&A sessions after sets of four to eight talks. Due to timezone issues not every speaker was around when their talk was shown. For this, Discord provided a useful medium to record questions that were asked and allow answers (and follow-up discussions) to be posted asynchronously. Furthermore, these text chats provided rich sources of information even after the conference.

#### Poster sessions

The poster sessions turned out well, perhaps even better than in person as you could actually have a conversation without too much background noise. Posters were presented in a dedicated ‘Poster building’ in Remo, with each presenter assigned a table, where they could attach multimedia materials in advance to a dedicated “whiteboard” and chat interactively with visitors. This building was available for the entire duration of the conference. The displays included anything from a downloadable PDF to videos, interactive slides, sticky notes, images, hyperlinks and more.

&nbsp;

<div style="border:1px; border-color:black; border-margin:10px;">
<img src="../img/posts/poster-table.png" alt="Remo poster table/whiteboard" width="100%"/>

<b>Figure 4</b>: Example of a poster table (whiteboard) in Remo. Poster presenters could add text and figures, embed videos and links, and discuss with other people at the table.
</div>


#### Challenges

In many ways, planning a virtual meeting is more difficult than planning an in-person one. Due to the fact that none of the organisers and very few of the attendees had previous experience with Remo, a lot of training material and demo sessions were required, all in a very short time frame. And due to a mix of technical limitations in Remo (mostly the number of participants who can talk at once) and unfamiliarity with how to use it led some training session leaders and BoF organisers to use Zoom or Google Meet. As if we didn’t have enough platforms in use already!

On-the-ground support required more work than for an in-person meeting. Most of the user support questions came from people who could not log in to Remo, which happened when they used a different email address from the one specified at registration (through Eventbrite). Remo’s option to log in through Google didn’t help when attendees had registered with a non-Google address. Technical issues with sound and voice arose but could often be fixed by reloading the browser tab running the Remo session.

Even though we kept the virtual conference days shorter than in an in-person meeting (five hours vs eight or nine), screen fatigue kicked in eventually and there was limited interest in social gatherings after the sessions. Group socializing was also hampered by the different time zones attendees were located in. And, most importantly, not everyone was able to shield themselves from the new normal life continuing around them, which could have meant family members to look after, chores to run, etc. All of these factors would have been in play at any virtual meeting, of course, regardless of the technology used to run it.


<div style="border:1px; border-color:black; border-margin:10px;">
<img src="../img/posts/worst-parts.png" alt="Exit survey results about worst parts of BCC2020" width="100%"/>

<b>Figure 5</b>: Exit survey opinion on the worst/not worth it parts of BCC. Of 78 respondents, 65.4% of people had no complaints.</div>


#### Tips for organizing an online conference in Remo and Discord

For those interested in organising their own conference here are a few tips we have learnt:

##### Before the conference

Attend one of the weekly **Remo demo sessions**.

Use a **free Remo trial account** to run a test event (see remo.co for more info).

Be careful with **naming test events**! We used the name BCC2020 in a trial account, and then were not able to use that name for our official account.

Providing **hands-on training** sessions for volunteers and organizers made a big difference. Experiencing Remo for the first time makes you realise that it’s different, but you get used to it very quickly. Most session techs and chairs got the hang of running a session after one or two test runs.

Set up a separate **team-chat platform** (in our case Discord) in parallel to Remo, not only for Q&A but also for help desk function and particularly for communication amongst organisers. Having multiple technology platforms increases the chance of participants getting ‘lost’--being unsure where the next session is, or how to locate a person or poster. Make sure to have plenty of **signposts** between the two.

Set up a **calendar bot** in Discord that notifies attendees of the Remo URL where the next session will take place. We used a combination of Google Calendar and [Zapier](https://zapier.com/) to post information about the next session in a dedicated Discord channel. Zapier offers a 14-day free trial, which is just enough time to set everything up and run through the conference with the finalized schedule.

Remo lets you <a href="https://help.remo.co/support/solutions/articles/63000252840-how-to-create-a-custom-floor-plan" alt="Custom Remo Floor Maps"><strong>design your own floor maps</strong></a> with tools such as Adobe Illustrator or Sketch. Thanks to example SVG files provided by Remo and an [online validator](https://live.remo.co/custom-floor-plan-validator), this is pretty straightforward. Our Remo floor plans are available as scalable vector graphics from a [Github repository](https://github.com/khokamp/Remo-Floormaps).

Consider setting up **different Remo buildings** for different purposes. In our poster building, we chose to make our tables seat eight people (the largest supported number) rather than the default number (six).  Our poster building included **sponsor tables**, where conference sponsors could chat with attendees, much like in the poster hall at an in-person meeting. We also added **job tables**, where attendees could post job ads or resumes. We designed different floor maps for the talk buildings and the BoF and training rooms, including two-seater tables for one-on-one meetings.

Since Remo fills event spaces, such as the poster building, from the bottom up, most **new arrivals came in on the first floor**. The posters that had been randomly assigned to that floor got more traffic. Rather than assigning posters to the first floor, fill it with sponsor / job / ads tables, and have side tables as the first point of entry so that no poster gets preference and participants can choose which poster table to jump to.

We ran **open houses** in multiple time zones the week before the conference started, which allowed attendees to familiarise themselves with the platform and work out any issues (e.g., trouble logging in).

Remo is still an actively evolving platform. Watch out for **Remo updates** (announced in their [blog](https://remo.co/blog/)) - they seem to happen mostly on Mondays. A few days before the start of the conference, Remo completely changed the settings interface, which required updating the training material. Keep an eye on the [Remo Roadmap](https://remo-conference.nolt.io/) for upcoming new features.

##### During the conference

Urge attendees to double-check their **email address** when registering and stick to that one when logging into Remo.

If possible, **divide the duties** of running a session between a chair and a tech person. Provide them with a checklist that details the various tasks (as in this [example](https://docs.google.com/spreadsheets/d/1Q4dGBfjJEJ91JQpLQh9WMkCAcFcmlaPGnRtzhwT5Xcc/edit?usp=sharing)). Also, when recruiting volunteers, provide information regarding what each role entails.

Besides presenting a recorded talk by playing it through a shared screen, Remo offers the possibility to **stream videos** from popular online platforms, such as YouTube or Vimeo. This avoids bottlenecks and reliance on a single computer. Having videos online also enables repeated viewing after the conference. We went with Vimeo because of restrictions in YouTube’s license agreement regarding broadcasting of videos.

When streaming videos be aware that due to **delayed starts or buffering** some attendees might still be watching the end of a video while others have finished. For multi-talk sessions it was useful to leave about 15 seconds of a break and put up a slide that indicated the current talk. Additionally, a timer bar could be shown to indicate the time remaining in a talk (particularly for those who entered the session late and missed the start of the video).

#### Summary

It is hard for virtual conferences to compete with in-person meetings. Some aspects of virtual meetings, such as lower costs and lower carbon footprint, are great and can increase the number of attendees and, in particular, encourage attendance from parts of the world that are typically underrepresented. Registrations more than doubled in our case compared to previous meetings. Remo provided a platform that encouraged interactions amongst participants and simulated the feeling of an in-person meeting. But the circumstances for each individual (time zone, surroundings, parallel commitments) simply can not be compensated for. Interestingly, of those who filled out the post-meeting survey and had attended BOSC or GCC before, nearly three quarters found the virtual conference to be just as good. And we received several requests to keep up a virtual component even if the next conference is in-person again. This seems a good indication that the way we organised the meeting, including our choice of platforms, worked well.

&nbsp;

<div style="border:1px; border-color:black; border-margin:10px;">
<img src="../img/posts/remo-qn.png" alt="Exit survey results about attendee opinion on Remo" width="100%"/>

<b>Figure 6</b>: Exit survey opinion on the Remo platform. Of 111 respondents, 83.7% gave Remo a 4 or 5 out of 5, and nobody ranked it a 1/5.</div>

&nbsp;

We hope these tips prove useful to you as you organise your virtual conference, whatever technology you end up choosing.
