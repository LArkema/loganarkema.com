---
title: 'The OSCP Blog Post'
date: 2021-9-5
permalink: /posts/2021/09/OSCP-blog-post/
tags:
  - OSCP
  - Security
  - Certifications
---

I feel that there's an unwritten rule that if (1) you have a personal website and (2) have passed the Offensive Security Certified Professional (OSCP) exam, then (3) you must write at least a little bit about "the OSCP journey." At the very least, this exam takes up a lot of people's time and energy so damnit we're going to write about it.   

This post went a little longer than I anticipated. My goal is to provide some insight into my thought process from start to finish and reflect on which elements of "the journey" were most worthwhile for me. However, there is pretty much nothing new here, other than my thoughts on where OSCP fell within the broader scheme of my life. As I alluded to, there are nearly infinite blogs on taking the OSCP, and this isn't anything special. [Rana Khalil's Blog](https://rana-khalil.gitbook.io/hack-the-box-oscp-preparation/my-oscp-journey-a-review) on the matter (as well as her technical blogs) were a great resource, and so was [Ian Coldwater's twitter thread](https://twitter.com/IanColdwater/status/1278508895233888257?s=20) on the exam.

If you're looking for my thoughts on a specific part of the OSCP process, here's a brief Table of Contents:

* [Why I Did the OSCP](#why-i-did-it-and-disclaimers)
* [Preparation Process](#the-process)
  * [PWK Course](#pwk-usefulness)
  * [Lab & Exercise Report](#lab-exercises-report)
  * [3rd Party Resources](#end-of-1st-pass)
  * [2nd Lab Access](#round-two)
    * [Last Months Pre-Exam](#refining-the-skillz)
    * [TJ NULL List](#tj-null-prep-list)
* [The Exam](#the-exam)
  * [Exam Report](#report-writing)
* [Final Thoughts](#final-thoughts)

## Why I Did It and Disclaimers

I want to start off by making something abundantly clear: You do _**not**_ need to have an OSCP. While the process was extremely educating and rewarding for me, you do not need to subjugate yourself to the grind of OSCP prep or the easily-toxic "try harder" mentality. The certification only directly applies to a specific subset of the infosec industry, and unless if you're focused on proving your mettle as a pen-tester, you can easily have a successful career without one (Very few, if any, other people at my workplace have one and most people I work with are smarter than I am).

So, why did I subjugate myself to this endeavor that will likely end up having a limited impact on my career? At a fundamental level, because I get bored easily, and I like to take on unnecessary challenges to force myself to learn more and demonstrate that people working in government / policy have technical chops. I am not saying this is a healthy character trait.

More specifically, I only ended up doing an OSCP because of a unique alignment of circumstances:

1. Covid. I just graduated college and needed something to do to occupy my newly found adult free time.

2. Scholarship Money. I was fortunate enough to participate in the [_CyberCorps_: Scholarship for Service](https://www.sfs.opm.gov/) program, which included a professional development stipend. Normally, I would have used the money to go to Cons, but those were cancelled because, again, Covid. Since it was use-or-lose, I took the free money to go for the OSCP (as well as [CySA+](https://www.comptia.org/certifications/cybersecurity-analyst)).

3. No other responsibilities. It's important to note that I was only able to use my abundant free time and scholarship money to grind on this certification because I was living independently with no one else to care for, a job that left me with enough mental energy at the end of the day to continue studying, and no other immediate issues that would have left me with less time for side-projects.

**My case is not the norm.** This very specific set of circumstances was the case for _very_ few people during the pandemic, and I think it would be ridiculous to assume that just because I had the resources and bandwidth to work on a certification during Covid, other people could have easily done the same.

> I would not have done the OSCP in normal circumstances. In hindsight, I probably did not take as much time for myself as I should have during a global pandemic, and I would strongly consider not doing it if I knew how much time and energy it would take. I would also not have taken it if I had to pay for it.

# The Process

I began the Pentesting with Kali (PWK) course in mid-August 2020, and initially purchased three months of lab access (again, use-or-lose scholarship money). However, I was still fairly new to my job and working on other side-projects at the same time (e.g. [ResidueFree](/publication/residuefree)), so by the time I had gone through the entire book and finished the course exercises, I only had a month left to work on the labs. 

> The lab time counts, and is, in my opinion, the best preparatory resource at your disposal. If at all possible, try to get funding for additional lab time and make sure you'll have as few competing priorities as possible during your month(s) of lab access. (More [below](#round-two)).

### PWK Usefulness
Though I have a solid technical background and have gone through enough coursework, conferences, CTFs, and Hack The Box machines to feel that I had a decent grasp on the basics of offensive security, I learned of a bunch of fantastic tips, tricks, and resources from the PWK book (I never watched a single course video). I really wish I could have had access to the book without burning my initial lab time, but nonetheless I learned a lot. 

### Lab Exercises and Report
I did end up doing the exercises and the Lab Report. I don't know if I ended up getting points for it (I had enough points to pass without), but it was definitely worth taking the time to try out some of the tools and techniques I had not used before (others were a bit of a waste of time). My final lab report ended being 265 pages, most of which was screenshots. Looking back, I would have taken more time to include the actual code I used rather than just throw in screenshots of the completed exercise as a "self-explanatory" answer.

For the lab machines and exam report, I ended up using a combination of Word and [Obsidian](https://obsidian.md/) to take notes and track the steps on machines. While Obsidian is great for copying and paste code and what's on the terminal, getting screenshots out of it is a pain. Since I used Word for the reports, I'd dump my screenshots in Word then merge the screenshots and code / terminal results after completing the box. It also doesn't hurt to jot down a brief narrative as you hack to make report writing easier, even if you don't end up using it.

### End of 1st Pass
By the time my first three months ended in mid-November, I had completed the lab exercises and ~20 lab machines. I was in a decent spot, but nowhere ready to take the exam. I took a break to focus on [ResidueFree](/publication/residuefree) and the CySA+ certification I also registered for with my scholarship money, while trying to keep my skills up with [Hack the Box](https://app.hackthebox.eu/), [TryHackMe](https://tryhackme.com/), [Ippsec videos](https://www.youtube.com/c/ippsec), and the [Holiday Hack Challenge](https://holidayhackchallenge.com/2020/). I spent most of my time on HTB, but there a few TryHackMe rooms that are excellent for OSCP (just search "OSCP" in TryHackMe to find them).

## Round Two
The best step I took going into the exam was registering for another month in the labs. I got back around to the OSCP labs in mid-March (also right before my exam attempt about to expire), after getting my work to pay for a month in the labs from the training budget. Taking the time to focus on the labs, the network topology, and the different techniques required to crack each box was incredibly beneficial. Some boxes crumbled like candy, others were much more difficult, but by the end I had access to all three subnets and compromised around 55 (of 70) boxes, including two of "the big four" (Pain, Gh0st, Humble, and Sufferance).

I used the forums occasionally, especially near the beginning (of my first time in the labs) to understand which boxes to start with and how the labs worked,  and near the end to know which boxes had dependencies so I could focus my last few days cementing my skills rather than trying to root a box I couldn't yet. I would definitely encourage anyone to use them when necessary, as getting a nudge at one sticking point can open doors to learn about many more vulnerabilities and attack techniques.

### Refining the skillz
Before I knew it, my deadline for the CySA+ exam was also fast approaching, so I had to take a pretty hard break for about five weeks to step into the Blue Team's shoes and prepare for that exam. After passing that exam, I had just over a month before my OSCP exam attempt expired. Again, the use-or-lose professional development money was why I had two certs with very close exam deadlines. Generally, I would not recommend preparing for two certs at the same time.

### TJ NULL Prep List
In that last month, I briefly purchased Hack the Box VIP to practice on the legendary [TJ Null OSCP prep list](https://docs.google.com/spreadsheets/d/1dwSMIAPIam0PuRBkCiDI88pU3yzrqqHkDtBngUHNCw8/edit#gid=1839402159). To be honest, I think the list has some false positives (i.e. boxes with techniques not covered by PWK or OSCP), and not everything on there will _directly_ reinforce skills you'll need for the OSCP. That said, the list recognizes this and the skills are still helpful to have, but if you can get the funding for more lab time, definitely spend time on the labs instead of focusing on the list.

> Importantly, I used the boxes leading up to the exam to reinforce the habit of taking screen shots at _every_ step and throwing output from various tools (even the basic ones) into Obsidian. By the time you take the exam, hopefully documenting everything will be second nature. You do not want to use your precious brain power remembering to document during the exam.

# The Exam
In the last week of July 2021, just shy of a year since starting the PWK course, I buckled down and took the exam. I started at Thursday at 11 AM, giving me some extra time to sleep in and get a proper breakfast and coffee before starting. The setup, check-in, and verification processes were straightforward (I did have to take some pictures on my phone then upload to my computer because of my webcam's limited resolution and somewhat fixed position on my desktop monitor), but by 11 I was connected to the VPN and off to the races.

You may find various blog posts or tweets providing details on how many machines are on the exam, their general point breakdown, and what skill you may expect to use. I'm not going to tempt Offensive Security's lawyers with something like that here, but if you find the same info floating around, it's probably accurate :). So I'll try to keep things as ambiguous as possible while still getting into my head space.

It did not take me long to get through the easier / methodological portions of the exam, so I had built up a solid number of points by 2:00 and could take a comfortable break for lunch. After the first three hours, I thought it was going to be smooth sailing.

> Even at the beginning, but especially later on, <u>be prepared for rabbit holes</u>. Seriously. Whatever rabbit holes you're used to encountering in the lab or HTB, know that the exam dials it up and you need to be ready to force your brain to look at something else if the thing that looks "interesting" isn't leading anywhere.

After lunch, progress slowed and it took me a bit longer to get a foothold into my next target. Less straightforward than the previous challenges, it required the signature OSCP critical thinking to really consider what's in front of you and how different pieces can come together (which was very satisfying to solve). By dinner, I had identified some potential privilege escalation routes and it was not long after dinner (and after wasting my time on a rabbit hole incredibly close to the gold mine) that I had another box done.

From there, things went much slower than I would have liked, and by 9 PM I was pretty worried about my chances of success. However, eventually after some googling and trying things out I got a foothold. By 11 PM I was one privilege escalation away from having enough points to comfortably pass (otherwise, with the lab report I _might_ have passed by the skin of my teeth). I was at the point where I was tired and it was taking longer than it should have to identify the PrivEsc route, and once I did (around 1 AM) my very tired brain was anxious to have enough points to pass before going to bed. So, I started throwing things I thought might work rather than taking the time to really learn about what was in front of me. This was a mistake.

By 3 AM I wasn't getting anywhere and was probably doing more harm than good, so I set my alarm for 8 AM to let my brain rest a bit before trying to get that last needed PrivEsc. Surprising no one, a few hours of sleep and a fresh cup of coffee can do miracles for one's ability to google properly, and before I knew it I had clear explanations of what I was looking at. A bit of tweaking with what I needed to do later, and another box was done with a very safe margin to pass. 

I had done the hackz by 9 AM Friday morning, and I spent the next hour triple-checking my notes, screenshots, and the rooted systems to make sure I had everything I needed to write the report. After that, I powered up Metasploit and tried, to no avail, to see if I could get anything to budge on the remaining target(s). 

At 10:45, a polite ding from the chat session with the proctors informed me I was done, my VPN session terminated, and it was just me, my terminals, and a report that needed to be written before 11 AM on Saturday.

## Report Writing
This is where time, particularly sleep, management comes strongly into play. Sure you may be able to hack for 24 hours, but will your brain be in a decent enough state to write words good in the 24 hours following? After eating a quick lunch, I got right into merging my screenshots and Obsidian notes into the OSCP report format and adding the narrative structure explaining the vulnerabilities and my exploit steps, as well as highlighting the underlying findings and adding the various summaries. 

Thankfully, I spend a good chunk of my job turning technical information into digestible and formal written projects, so I could do this even as 4 PM hit and my brain started to turn into hardening concrete demanding a nap.

While I probably spent more time on formatting and editing the content than I needed to for a fake report, by 5 PM I was confident in what I had, quadruple checked the names of my files to ensure they matched OSCP's format, and submitted the zip file.

# Final Thoughts

I proceeded to take a celebratory shot, eat some dinner, go to sleep, and spend the next day (Saturday) partying with friends in what was the first time since Covid my roommate and I had more than one or two people over. 

By Monday morning, I got the email informing me that I passed, and a few weeks later my certificate arrived, making me an Offensive Security Certified Professional!

OSCP was something to keep me occupied when having a social life was a bad idea, and I'd say it did its job. That said, I wish I could have spent more of that time checking in with people I no longer talked to on a regular basis or focused on building more community with those around me. I think the world needs a lot of things right now, and more Offensive Security Certified Professionals isn't necessarily one of them, but if it makes sense for you, go for it and best of luck!

![](/images/OSCP-cert.jpg)