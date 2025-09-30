---
content_type: page
description: Page two of a blog entry cataloging student progress and the final presentation
  for a group project on a labor contraction monitor for Nicaraguan hospitals.
draft: false
learning_resource_types: []
ocw_type: CourseSection
parent_title: BabyTrackr
parent_type: CourseSection
parent_uid: bb097725-8aab-b7d2-7e42-559fcd0fbc98
title: BabyTrackr - Page 2
uid: 1f285a39-6e3b-596b-f990-f46eed40d51c
---
\<\< {{% resource_link "bb097725-8aab-b7d2-7e42-559fcd0fbc98" "1" %}} 2 {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "3" %}} {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Next" %}} >>

{{< anchor "The_Smarts" >}}{{< /anchor >}}The Smarts, and How We Got There.

## *by Maysun M. Hasan*

Hi guys,

This is my first post so I guess I'm going to back track a little. Please excuse any spelling mistakes… I am the worst speller in the world. The first thing I did when I found out about this project is call my mom… I know, kind of lame but whatever. She is an OB/Gyn and she has worked in many different types of settings, the most relevant for us being in the labor room at a rural Bangladesh clinic.

She told me that during labor, healthcare professionals monitor a woman's contraction rate, and cervical dilation to judge the progress of labor. A woman can be in labor for many hours but only when her contractions are close together and intense, and she is at least 10 cm dilated, is she close to delivering. My mom had said that once the contractions are close together (approximately 3-4 minutes apart), a doctor should come to examine the patient, and see if everything is alright. The doctor needs to see how much the woman is dilated. If the woman is not dilated enough, she should be given drugs to lessen the contractions for a few more hours. The doctor should also check the position of the baby, and reposition it if it is necessary. All this should be done at approximately this stage of labor, because if the doctor checks later, it might be too late for an easy intervention. **So one thing our device should do is indicate when contractions are a 3-4 minutes apart (we should find a firmer number in literature) so that the doctor knows they need to be around.**

My mom had also mentioned that fetal monitoring during a contraction is also very important, especially to detect early fetal distress due to fetal hypoxia, and metabolic acidosis. What normally happens is what is called mirroring. As the uterus contracts, the fetus goes into distress and its heart rate drops, but should come up immediately after the contraction has ended. If it doesn't, and the heart rate stays down after the contraction has ended (called late deceleration or uteroplacental insufficiency) it indicates a fetus' inability to respond to stress, most likely due to lack of oxygen and invention by the doctor is necessary. **Thus knowing when a women is having a contraction, from start to end, is important information our device should delivery.** My mom said, the current method of doing this, in ill-equipped settings, is with a stethoscope. When a woman is having a contraction, the muscles harden, making it harder to hear the fetal heart beat. Thus the heart rate starting from when you can hear it indicates late deceleration. This hearing method is not optimal, so our device should address this.

Lastly, my mom told me that abnormal change in contraction rate is also important data. For example, if the contractions are going from 10 to 9 to 8 minutes apart to all of a sudden 10 again, something probably happened. This is most of the time not critical, like the mother needs to go to the bathroom or something, but either way she needs attention. **So our device should show when the contraction rate indicate that non-critical attention is needed.**

And lastly, my mom told me about uterine inertia. This is when the uterus atrophies, and if this happens, the mother should be rushed to a C-section. An indication from contraction rates for this is if the contractions go from 4 to 3 to more than 30 minutes apart. **Thus signaling when the uterus atrophies is something our device should do.**

A lot more long winded than I wanted to write but whatever. This is just what we believe our device should do along with **indicating the actual rate of contractions**, and possibly **intensity** and **duration**.

We plan on doing this with the Arduino. We talked to Paul about this. We want our device to be relatively cheap so all the women in the labor room can have one, so I was originally not loving the >$20 Arduino. A microprocessor is not really necessary here since only solid logic is involved. I was thinking we could make a new chip that would do only this. It would be cheaper than and not as bulky as the whole Arduino. However, Paul got me to change my mind. The microprocessor itself is very small and cheap (~$3), so we could program in one place and attach to the device somewhere else. This is a lot better than making a new chip (which is easy to design but probably a pain to manufacture).

So we know approximately what we want, and we know how to do it, the next step is doing it. We also need to know the input to our device: squeeze ball, EMG, flexi-force… etc, but that's a different story. Sorry about the novel guys.

[Back to top](#The_Smarts)

{{< anchor "Updates_4_24" >}}{{< /anchor >}}Updates 4/24

## *by \[LT\]*

### Updates

- Karina and \[LT\] made two switch prototypes (massacred a bear and used his leg for a big red button, attempted to stick a switch in the tiger- his guts were everywhere, but he's not bandaged)
- \[LT\] and Karina met with Paul Saturday (today 4/24) to begin logic for switches and work on logic for data storage (what information we want to collection, display and how)
- Our resistive flexi strain gauges have arrived!
- Paul can order us a display for our prototypes
- Maysun working on EMG sensor p.m. Sunday (tomorrow 4/25)
- \[AB\] and Grace, please feel free to reply to the team with updates on information on posts on blog!
- Maysun working on EMG

### Meeting Agenda (4/25)

- Update on sensor prototypes – Maysun, Karina, \[LT\] ~ 10 min
- Update on research – \[AB\], Grace ~ 10 min
- Decide deadlines for research, code and prototypes ~ 15 min
- Decide on display ~ 20 min
    - Graph or dips with LED
    - Just numbers and signal lights
    - Computer

Gantt Chart review ~ 5 min

List of to-dos and to-blogs ~ 5 min

**Total** ~ 1hour 5 min

[Back to top](#The_Smarts)

{{< anchor "Research" >}}{{< /anchor >}}Research

## *by \[AB\]*

Hi all,

Here were the three topics I just researched for discussion at the next meeting:

1. Complications during pregnancy--uterus twitching
2. What else occurs when contraction happens, how flexiforce can be used
3. How to make a partogram

For (1) I found a helpful Web site that lists all the [disorders that occur during pregnancy](https://web.archive.org/web/20230209020910/https://www.medicinenet.com/script/main/art.asp?articlekey=40878). All high-risk patients should already be monitored closely, and those include: women with chronic hypertension, diabetes, lupus, incompetent cervix, placenta previa, preeclampsia, premature birth, recurrent miscarriages, and thyroid disorders. I think the disorders we should worry about are connected to the uterus in some way and might give false positives when using the belt we're building:

A) Fibroid Tumors: They are usually undetected non-cancerous masses that occur in the uterus, that go easily undetected in the third trimester of labor. There are four different types of fibroids in the uterus, subserosal, Intramural, submucosal, and Pedunculated. The one that might affect the size of the uterus and is the most common is the Intramural Fibroids, because they develop within the uterine wall and makes the uterus feel larger than normal. This causes pressure and pelvic pain. Another one that could also grow outside the uterus is the Pedunculated fibroids. This enlargement might be confused with the pressure that a contraction makes if we use the flexiforce so we should see if we can use another type of monitor, such as the partogram, which measures the cervix dialation, can be used alongside the flexiforce belt.

B) Placental Abruption: The placenta carries all the nutrients and O2 to the baby in the uterus from the mother. There are two extremes to this disease. Minor abruption may irritate the uterus and cause induced labor, but usually the baby is safe. The other type is Massive abruption, which may result in early labor and delivery, fetal intolerance of labor so C-section is required. There should be a way to measure this abruption. The causes of this abruption are usually unknown but could be caused by injuries to abdomen, use of drugs, high blood pressure, or chronic diseases such as diabetes. All pregnant women with these complications should be closely monitored already, but if it happens while the woman is in the hospital, I think we should have a way to detect it, I believe that slowing down of contraction rate might not be the only way to tell if the placenta has ruptured. After some more research, I found that there is usually pain in between contractions, so we should have some sort of button or monitor of intensity of pain between contractions to check for complications as well? I don't know how to do this without having an honor code for the women because they are the ones in pain. There is also vaginal bleeding so that might be easier to detect and then there is abdominal pain that remains constant throughout labor, which should not be confused with increase rate of contraction.

C) Uterine twitches: A normal contraction will occur by shortening and thickening of uterine wall muscle fiber. The contraction starts at the top of the uterine wall and waves down to the bottom. When "true" labor begins, women feel "false" labor pains, or a Braxton Hicks contraction, which is irregular uterine contractions that occur in the second or third trimester of pregnancy. They're the body's way of getting ready for the "real thing." They feel like a tightening in the abdomen that comes and goes. They do not get closer together, do not increase with walking, don't increase how long they last and don't feel stronger over time. Here is a table that doctors ask their patients over the phone apparently:

{{< tableopen >}}{{< theadopen >}}{{< tropen >}}{{< thopen >}}
CONTRACTION CHARACTERSTICS
{{< thclose >}}{{< thopen >}}
FALSE LABOR
{{< thclose >}}{{< thopen >}}
TRUE LABOR
{{< thclose >}}{{< trclose >}}{{< theadclose >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
**How often do the contractions occur?**
{{< tdclose >}}{{< tdopen >}}
Contractions come at regular intervals and last about 30-70 seconds. As time goes on, they get closer together.
{{< tdclose >}}{{< tdopen >}}
Contractions come at regular intervals and last about 30-70 seconds. As time goes on, they get closer together.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
**How strong are they?**
{{< tdclose >}}{{< tdopen >}}
Contractions are usually weak and do not get much stronger. Or they may be strong at first and then get weaker.
{{< tdclose >}}{{< tdopen >}}
Contractions steadily increase in strength.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
**Do they change with movement?**
{{< tdclose >}}{{< tdopen >}}
Contractions may stop when you walk or rest, or may even stop if you change positions.
{{< tdclose >}}{{< tdopen >}}
Contractions continue despite movement or changing positions.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
**Where do you feel the pain?**
{{< tdclose >}}{{< tdopen >}}
Contractions are usually only felt in the front of the abdomen or pelvic region.
{{< tdclose >}}{{< tdopen >}}
Contractions usually start in the lower back and move to the front of the abdomen.
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}

When twitching occurs, there is no wave-like movement of the contraction, so there is a distinct difference between the two. The twitches are more like a spasm, and also they occur in women who are not pregnant as well, and do not cause pain so there is another difference between contractions and twitches/spasms. One last little tidbit, which you guys might know already: women in the US go to the hospital with contractions occur every five minutes for an hour.

2) I am still researching what else occurs during contraction other than water breaking, not in all cases, cervix dilation and random bowel movements that women can't control.

3) I think we should try and make partograms, they're pretty easy and can monitor dilation, fetal heart rate, duration of labor and vital signs. That way delay or deviations of labor can be detected more easily than depending on contraction rate deviations. It also shows a numerical record of features such as urine output and the volume and type of intravenous infusions (including oxytocin drips):

Image removed due to copyright restrictions. Please see image and explanation of a partogram at [http://www.2womenshealth.com/Childbirth/Partogram.htm](http://www.2womenshealth.com/Childbirth/Partogram.htm)

There are two-hour partograms and four-hour partograms, but I think the best one is to do a two-hour study (approved by WHO, because it increases the need for intervention without improving maternal or neonatal outcomes compared to four-hour partogram) and when the labor looks slow, the doctor will do something about it. Doctors say that a rate below the average (1 cm/h) shows a slow labor. First, they rupture the amniotic sac and then give oxytocin to stimulate contractions and labor. Partograms must be used along with the belt because when doctors stimulate contractions, careful monitoring should be made to ensure that contractions do not exceed one every two minutes. If this stimulation doesn't help, then the doctor will perform a C-section, only after the mother's consent.

I think the nurse or health official needs to keep track of this though, which may be a problem if there are more than five women in the ER. There is also clinical pelvimetry, which is used to monitor the size of the birth canal by means of systematic vaginal palpation of specific bony landmarks in the pelvis and the estimation of the distances between them. Internal pelvic diameters are not accessible, so usually midwives or a doctor will infer. This occurs at the first prenatal check-up (do they have those in Nicaragua??) and they're recorded as adequate, borderline, or inadequate, rather than in cm or inches.

Maybe that might be a better idea than partogram? However, I think that we should still make a chart for the partogram and see if it's intuitive enough for the doctors to use…

Anyways that's what I've researched so far…will keep you guys updated on anything else i find. Sorry for the long post!

[Back to top](#The_Smarts)

## {{< anchor "Quick_Question" >}}{{< /anchor >}}Quick Question

So I know I couldn't go to the meeting with Jose which may have been where I missed this, but whatever happened to the part about helping mothers know when to call the ambulance? I thought that based on what Ryan said about his personal experience and on one of the problems we had identified in Nicaragua, which was not having babies on the side of the road, we were going to make a home-use component too. Are we not doing that anymore? It seems like this is purely for use by health workers at the hospital - which is okay I guess; I just would like someone to justify why.

[Back to top](#The_Smarts)

{{< anchor "Button_Logic" >}}{{< /anchor >}}Button Logic Pseudocode and Visuals

## *by Grace Yao*

So this is what we talked about in class today, besides looking at the button models \[LT\] and Karina made and eating M&M's from Anna!

Here's a vague idea of how we want the button to work…

boolean down #true = button is pushed down

\# 3 states: notContracting, checking, contracting

if state == "notContracting" and down:

   state = "checking" # change the state

if state == "contracting" and !down:

   state = "checking" # change the state

if state == "checking":

if (down for >= 5 seconds): # 5s so nothing will be counted mistakenly. need to somehow start timing when down changes from t->f or f->t?

   state = "contracting"

elif (!down for >= 5 seconds):

   state = "notContracting"

Visuals should include these:

1. The display should have 2 rows of numbers, top row = duration of contraction in seconds, bottom row = duration of time in between contraction in minutes; these numbers would preferably be offset from each other in a zigzag, but we'll see depending on what the monitor looks like.
2. The two little number counters should show   
      
    a) Rate (how many contractions in the last hour) and   
      
    b) Time since the last contraction
3. Three differently-colored LEDs.   
      
    a) Contraction button is pressed,   
      
    b) when the baby is about to come, aka when rate = 10 contractions/hr and time in between contractions = 5 minutes, and   
      
    c) When there may be a complication -> steady if not urgent, blinking if urgent.
4. Maybe a row of LEDs to show intensity?

{{< anchor "Meeting_4_28-_" >}}{{< /anchor >}}Meeting 4/28- What we're Up To!

## *by \[LT\]*

 

{{< resource uuid="7be116d8-fb6a-1d1a-c983-2a20c66b7cb3" >}}

 

Gantt Chart

Hi Everyone,

The Gantt indicated when each step should be finished!

A new quick capacitor idea: Maysun will work on putting one with conductive metal, a belt to constrain it, wire, and rubber from bicycle inner-tube from D-Lab to prove that it might be more viable than the EMG and pick up on contractions by change in capacitance. She suspects that EMGs might not be robust enough and the electrodes must be disposable.

The capacitor will work off displacement of the muscle and be slightly pressed on the woman's stomach. When the muscle tenses, the plates will close up, and we should observe some change.

Grace and I will be finishing up the general code and the screen to display contraction data has been ordered by Paul and should be coming soon. Karina and I will finish the actual button on Sunday. Grace and \[AB\] will be starting up the poster. Please comment to this if I forgot something!

[Back to top](#The_Smarts)

{{< anchor "EMG_Plan" >}}{{< /anchor >}}EMG Plan

## *by Maysun M. Hasan*

Hi guys,

So I should have posted this about a week ago, but my computer died and stuff happened so it never got posted. This is the plan for the EMG.

The **Electromyography** (EMG) is a technique of recording the electrical activity in muscles. So the principle theory is that uterine contractions are caused by a series of action potentials that will cause a voltage change that can be detected, similar to how an ECG works. So how should we go about making an EMG? First we need a way to detect electrical activity. We can do this with a differential amplifier. The voltage difference is measured from two electrodes, which are placed relatively close together on the surface of the mother belly, (on the uterus). They are compared to ground, which is place on the mother's hip, where there is no muscle activity. The Diff Amp should output a signal like below, which is an EMG for a bicep:

{{< resource uuid="d02a3c0e-7d9e-db96-eac1-c7b7498464d6" >}}

Image by MIT OpenCourseWare.

This signal has been high and low passed filtered, which is something our circuit needs to do. The signal should then be rectified so that only the positive part of the signal is kept, like below.

{{< resource uuid="e5b89f83-f368-aae5-eba1-7af7396a2f6e" >}}

Image by MIT OpenCourseWare.

Finally, we need to smooth our signal out so that we form an "envelope", as seen below.

{{< resource uuid="ed251d8e-b4ef-257d-3a43-f47592a80da2" >}}

Image by MIT OpenCourseWare.

So our overall EMG system is described in the flow chart below.

This is our plan. Let's see how it goes. I think getting the Diff Amp to give a signal, which is really small, and filtering all the noise is going to be the hardest parts. Since we lack a pregnant women, we will be testing our system on our arms. \[AB\] and I tried to get electrodes from MIT Medical, but ended up getting the run around and failed miserably in our quest. But fortunately my friend Ankit said that he could get us electrodes. So all is well, I hope, at least we'll see when we start building.

Source: ([PDF](http://web.archive.org/web/20141130125653/http://www.ece.utah.edu/~harrison/ece3110/Lab5.pdf))

[Back to top](#The_Smarts)

{{< anchor "Playing_Around" >}}{{< /anchor >}}Playing Around With Different Materials, Toys and Arduinos

## *by Karina Isaak*

Here are some pictures of our experiments with different sensors (buttons) and materials for the contraction monitor ball, that the women in labor squeezes if she is having a contraction.

Our favorite is the big red button (picture 1) put into a latex glove which is filled with cotton (pillow stuffing). It is soft, comfortable, cheap, easy to produce, robust and reliable.

We also started programming the Arduino to record when the ball is squeezed, indicating that the women are having contraction. Grace posted the pseudo code that we are working on.

The next step will be to connect it to the display and get everything running!  
{{< image-gallery id="1f285a39-6e3b-596b-f990-f46eed40d51c_nanogallery2" baseUrl="/courses/ec-710-d-lab-medical-technologies-for-the-developing-world-spring-2010/" >}}  
{{< image-gallery-item href="a4f29ae628caf6c910b4c9aa23874ef4_gallery3img1.jpg" data-ngdesc="Big red button" text="Big red button" >}}  
{{< image-gallery-item href="1ba0044b509da0ca84557653a1194b1b_gallery3img2.jpg" data-ngdesc="Prototype with circuit board." text="Prototype with circuit board." >}}  
{{< image-gallery-item href="2b9c9daa4adfb1c1bed1667097e3b89f_gallery3img3.jpg" data-ngdesc="Couscous" text="Couscous" >}}  
{{< image-gallery-item href="fb1355db1888a07036db8e02cbaa6ab4_gallery3img4.jpg" data-ngdesc="Cotton" text="Cotton" >}}  
{{< image-gallery-item href="57ce3bf5f358f4e45465172f5075516f_gallery3img5.jpg" data-ngdesc="Dirt/Sand" text="Dirt/Sand" >}}  
{{< image-gallery-item href="daf1a541357c73afa1bcffc038a43996_gallery3img6.jpg" data-ngdesc="Foam" text="Foam" >}}  
{{< image-gallery-item href="3ceac5f40e983a1c0bd569ece42e8f12_gallery3img7.jpg" data-ngdesc="Four test materials with squeeze toys." text="Four test materials with squeeze toys." >}}  
{{< image-gallery-item href="309aee961e455f6ebb011d8afff6f898_gallery3img8.jpg" data-ngdesc="Squeezing a toy ball." text="Squeezing a toy ball." >}}  
{{< /image-gallery >}}  
\<\< {{% resource_link "bb097725-8aab-b7d2-7e42-559fcd0fbc98" "1" %}} 2 {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "3" %}} {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Next" %}} >>