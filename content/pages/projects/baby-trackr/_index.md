---
content_type: page
description: Blog entry cataloging student progress and the final presentation for
  a group project on a labor contraction monitor for Nicaraguan hospitals.
draft: false
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: fd032552-908b-39df-9f46-c936d1092c8c
title: BabyTrackr
uid: bb097725-8aab-b7d2-7e42-559fcd0fbc98
---
{{< anchor "Labor_contraction_monitor_for_Nicaraguan_hospitals" >}}{{< /anchor >}}*Labor contraction monitor for Nicaraguan hospitals*

Team: Maysun M. Hasan, Grace Yao, Karina Isaak, and anonymous MIT students \[LT\] and \[AB\]

This content is presented courtesy of the students and used with permission.

1 {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "2" %}} {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "3" %}} {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "Next" %}} >>

- [Welcome to the Contraction Monitor team blog!](#Welcome)
- [April 15 Post](#April_15_Post)
- [April 16 Post](#April_16_Post)
- [April 19 Post](#April_19_Post)
- [Patents for various contraction monitors](#Patents_for_Various)
- [Retroactive post](#Retroactive_Post)
- [Team Info, Revised Problem Statement, Some early brainstorming thoughts (Pugh Chart, Design Specs)](#Team_Info)
- [Pitch](#Pitch)
- [Re-direction of our Project](#Re-direction)
- {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "The Smarts, and how we got there" "#The_Smarts" %}}
- {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "Updates 4/24" "#Updates_4_24" %}}
- {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "Research" "#Research" %}}
- {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "Quick Question" "#Quick_Question" %}}
- {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "Button logic pseudocode and visuals" "#Button_Logic" %}}
- {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "Meeting 4/28- What we're up to!" "#Meeting_4_28-_" %}}
- {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "EMG Plan" "#EMG_Plan" %}}
- {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "Playing around with different materials, toys and Arduinos" "#Playing_Around" %}}
- {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Cloth patch for monitoring contractions!" "#Cloth_Patch" %}}
- {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Home stretch" "#Home_Stretch" %}}
- {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Response from Nicaragua" "#Response_From" %}}
- {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Instructable" "#Instructable" %}}
- {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Pennies for your muscles" "#Pennies" %}}
- {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Convo with Dr. Acker" "#Convo_with" %}}
- {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Radio awesomeness" "#Radio_Awesomeness" %}}
- {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Logo" "#Logo" %}}
- {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Alien Mind Control!!!" "#Alien_Mind_" %}}
- {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "Presentation at MIT Museum" "#Presentation" %}}
- {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "More action shots PLUS interested Physician from Brazil!" "#More_Action_Shots_PLUS" %}}

{{< anchor "Welcome" >}}{{< /anchor >}}Welcome to the Contraction Monitor team blog!

## *by Grace Yao*

By the way, should we try to come up with a catchier name, maybe like Laborsaver or something like that? Just a random thing I thought of!

In any case, we are \[AB\], Maysun Hasan, Karina, \[LT\], and Grace Yao, and here is a little bit about the problem we are trying to solve and our goal for the solution.

In developing countries, such as Nicaragua, maternal health is very rudimentary in rural areas. Usually community health care workers make house visits to check up on the mothers, but they have limited knowledge and resources for proper maternal care. Also, mothers have to decide when to go to the health posts to address their concerns if any problems arise. When labor gets to a certain point, the ambulance has to be called to transport the mother to a hospital, which is often very far away. Often, it is hard for the mother to determine when she needs to call an ambulance. In worst-case scenarios, the mother doesn’t call in time for them to reach the hospital, and they must deliver the baby on the side of the road. To avoid such cases, we have proposed to develop a monitor to automatically alert different stages of labor based on contraction rate. The monitor should signal for when a contraction occurs, its length and rate, when the ambulance needs to be called, when critical attention is needed, when non-critical attention is needed, and when the baby needs to be delivered. The signals (in addition to the one for calling the ambulance) may aid health care workers in quickly identifying which mothers need attention at a birthing facility, helping them triage the patients.

[Back to top](#Labor_contraction_monitor_for_Nicaraguan_hospitals)

{{< anchor "April_15_Post" >}}{{< /anchor >}}April 15 Post

## *by Karina Isaak*

Hi team,

I just found this article which was published in May 2009.

Haws, Rachel A., Mohammad Yawar Yakoob, Tanya Soomro, et al. "[Reducing Stillbirths: Screening and Monitoring During Pregnancy and Labour](http://www.biomedcentral.com/1471-2393/9/S1/S5)." *BMC Pregnancy and Childbirth* 9, 2009.

It gives a review of the interventions used worldwide to prevent stillbirths.

Please, take a look at the section called

**Monitoring in Labour**    
*Use of the partograph*

starting on page 33.

They are talking about monitoring the contraction with a partograph, That's kind of what we want to measure with our device. In the results section they say that even though they couldn't find significant differences in maternal or perinatal outcomes with the use of partograph versus no partographs, it can still help in low-resource settings:

"Partographs may be comparatively more effective in low-resource settings, as the studies from Africa and Mexico in the Lavender review \[140\], as well as data from Southeast Asia \[146\] that showed reduced Caesarean section rates with use of the partograph and early intervention for slow progress of labour. The data from Southeast Asia and Indonesia also showed trends toward improved birth outcomes \[146\]." (Haws, et al., 2009, p.34)

Their statistical analysis was probably insignificant because of "unclear guidelines on the partograph use" (Haws, et al., 2009, p. 35). Therefore, building an intuitive device that is working with the partograph could possibly help to prevent stillbirths in developing countries.

What do you guys think?

[Back to top](#Labor_contraction_monitor_for_Nicaraguan_hospitals)

## {{< anchor "April_16_Post" >}}{{< /anchor >}}April 16 Post

Hey team,

Grace, I agree, we definitely need a more creative name… let's brainstorm about it in class today. Here is a study comparing the EMG contraction monitor to a tocotransducer belt. EMG seems to be the better way to measure contractions.

Maul, H., W. L. Maner, G. Olson, et al. "[Non-Invasive Transabdominal Uterine Electromyography Correlates with the Strength of Intrauterine Pressure and is Predictive of Labor and Delivery](http://informahealthcare.com/doi/abs/10.1080/14767050410001695301)." *Journal of Maternal and Fetal-Neonatal Medicine* 15, no. 5 (2004): 297-301.

Let's first test the resistive flex sensor \[LT\] ordered and then start working on the EMG/EKG if the sensor turns out to be not reliable for measuring contractions.

[Back to top](#Labor_contraction_monitor_for_Nicaraguan_hospitals)

{{< anchor "April_19_Post" >}}{{< /anchor >}}April 19 Post

## *by \[AB\]*

Hey all,

Hope you're enjoying the long weekend! I found another interesting article that shows how an external taco meter is just as good as an internal one, although the internal one uses pressure gauges. Just to confirm that we should make both an EMG and an external tocodynamometer. Anyways, I also think we could think of a better name. So I looked up LaborSaver, and apparently it's already a product that allows workers to save money. How about laborhelper? Regardless, here's the article.

Bakker, Jannet J. H., Corine J. M. Verhoeven, Petra F. Janssen, et al. "[Outcomes after Internal Versus External Tocodynamometry for Monitoring Labor](http://www.nejm.org/doi/full/10.1056/NEJMoa0902748)." *New England Journal of Medicine* 362, no. 4 (2010): 306-13.

Here's another article I found on how to make an embedded microcontroller and EMG:

Wu, Han-Chang, Chao-Hung Lin, Shuenn-Tsong Young, et al. "[Monitoring Long-Term Uterine Contractions](http://ieeexplore.ieee.org/xpl/freeabs_all.jsp?reload=true&arnumber=1005658)." *IEEE Instrumentation and Measurement Magazine* 5, no. 2 (2002): 36-40.

I think it's very similar to what Maysun sent out a couple days ago.

Let's meet up some time (I think we're agreeing for tomorrow 3 pm) to discuss specs and how to make both of these.

[Back to top](#Labor_contraction_monitor_for_Nicaraguan_hospitals)

{{< anchor "Patents_for_Various" >}}{{< /anchor >}}Patents for Various Contraction Monitors

## *by Grace Yao*

[Apparatus for non-invasive monitoring of uterine contractions](https://pubchem.ncbi.nlm.nih.gov/patent/US-5195536-A)    
United States Patent 4989615

From Abstract: "An apparatus which includes a bladder element (10) which is at least partially filled with fluid, a belt-like element (12) which holds the bladder against the patient's abdomen with some pressure, and a pressure monitoring device (18) which is connected to the bladder (10) to detect changes in the pressure of the fluid in the bladder (10) as the abdomen hardens due to uterine contractions."

[External uterine contraction monitoring device](https://patents.google.com/patent/US5070888A/en)    
United States Patent 5070888

From Abstract: "An improved monitoring device for externally monitoring labor contractions preceding childbirth which does not require the use of a belt is disclosed consisting of a transducer removable assembly fixed to a base adhesively attached to the abdomen of the woman."

[Disposable tocodynamometer with self-adjusting bellows](https://patents.google.com/patent/US5224490A/en)    
United States Patent 5224490

From Abstract: "A non-invasive, disposable, self-adjusting tocodynamometer (10) for monitoring uterine contractions of a patient during pregnancy, labor, and delivery The tocodynamometer includes a pressure-sensitive, fluid. filled bellows (20) responsive to changes in the hardness of the uterus during contractions The bellows has one face which projects into the patient's soft tissue in the abdomen and adjacent the uterus, rending the tocodynamometer sensitive even for obese patients. A plate (22) supports the bellows and provides structure for attaching the tocodynamometer to the patient. A wall (30) formed on the plate receives the bellows as it is compressed during use. A conduit (14) connects the bellows to a pressure transducer (12) which, in turn, is connected to a monitor (16). The bellows, conduit, and pressure transducer form a closed system containing the working fluid."

[Back to top](#Labor_contraction_monitor_for_Nicaraguan_hospitals)

{{< anchor "Retroactive_Post" >}}{{< /anchor >}}Retroactive Post

## *by Grace Yao*

This is where we were 5 days ago, before the meeting with Jose:

Below is a list of Ob/Gyn's in Boston that I grabbed from [thecityofboston.com](http://www.thecityofboston.com/physicians/ob-gyn-physicians.html). I think we've pretty much decided on using the simpler on/off indicator as opposed to measuring force with varying intensity. So what we really need to find out now on the medical side of things is:

What are the times we have to measure to know the things we want to indicate, which are

1. when the mother should go to the hospital
2. when the mother needs attention but not critical
3. when the mother needs critical attention
4. when the doctor needs to be there to deliver the baby.

Then the 5th thing we're having a light for is an indicator of when she's actually having a contraction, which is pretty straightforward.

Other things we have to figure out:

Materials: what kind of material for the squeezy part? The wire connecting the ball/wristband should have a covering too right? What is the wristband going to be made out of? We want to look into refractive materials so that we can just use one light to light up a lot of the wristband.

Smarts: Microcontroller? Something else? Maysun, can you maybe summarize what you talked about with Paul?

User Interface: How much information should the mother have? How are we going to display it?    
(Number/graph/both?) Do we need to design a radio component too? Would sound be better?

Acker, David B MD - Brigham Women's Hospital

75 Francis St Ste ASB1

Boston, MA

(617) 732-5445

Etkin, Masha J MD - Vincent Obstetrics/Gynecology Associates

32 Fruit St Ste 4E

Boston, MA

(617) 726-1753

Gomez-Carrion, Yvonne MD - Beth Israel Deaconess Women's

330 Brookline Ave Ste KS205

Boston, MA

(617) 667-2952

Johnson, Kim M MD - Kim M Johnson MD

500 Brookline Ave Ste E

Boston, MA

(617) 732-6399

Moody, David B MD - David B Moody MD

45 Francis St

Boston, MA

(617) 732-6389

Perkins, Rebecca B MD - Rebecca B Perkins MD

85 E Concord St

Boston, MA

(617) 638-8000

Rodriquez, Elisa MD - New England Medical Center

860 Washington St Ste 2

Boston, MA

(617) 636-6114

Taylor, Faye - Boston Medical Center

91 E Concord St Ste 6

Boston, MA

(617) 414-5461

Wakamatsu, May M MD - May M Wakamatsu MD

55 Fruit St Ste 148

Boston, MA

(617) 726-2000

Yum, Mimi MD - Mimi Yum MD

330 Brookline Ave

Boston, MA

(617) 667-0478

[Back to top](#Labor_contraction_monitor_for_Nicaraguan_hospitals)

{{< anchor "Team_Info" >}}{{< /anchor >}}Team Info, Revised Problem Statement, Some Early Brainstorming Thoughts (Pugh Chart, Design Specs)

## *by \[LT\]*

Hi! This is also sort of a retroactive post. We are the Contraction Monitor team!

When a woman goes into labor, clinics are not equipped to monitor her contractions- an important indicator of her stage of labor and any complications. Health workers currently rely on their hands on the woman's stomach to time the contractions, fetal heart rate, and feel for the relative intensity. This can be a time and labor intensive method, especially when 8-10 women are in labor at the same time in the same room. We have proposed to develop a monitor to automatically alert different stages of labor based on contraction rate. Additionally, it will give the relative intensity of the contraction and output a graph with the contraction frequency. The monitor should signal for when labor has started, when a contraction occurs, its length and rate, when critical attention is needed, when non-critical attention is needed, and when the baby needs to be delivered.

**Some thoughts from early brainstorming:**

Should we be wary of giving to much info to mother? consider external monitor

Distributed beforehand? when starts feeling contractions, puts it on, tells her when she needs to go to hospital based on timing (how much time she has left, etc.), then switches to more accurate mode with wireless broadcast. Have extra **mode** or signal for when to go to hospital?- **Since we've revised our problem statement, this is no longer a priority need!**

Talk to potential users about what signals to use, and whether she rather know or now know, and what would stress her out

The iPhone® app contraction monitor has start time, end time, duration, and frequency. Has a timer, and history. Another app gives the graph.

Thought for Ball contraction monitor: info sent to doctor's phone.

**See below for our Pugh chart and Prelim Design Specs!**

{{< resource uuid="3609e5f4-369e-c324-572f-235d3dc9ac59" >}}

Pugh Chart

{{< resource uuid="10cd268b-7e2c-93ff-8478-704c14b263a3" >}}

Design specifications

[Back to top](#Labor_contraction_monitor_for_Nicaraguan_hospitals)

{{< anchor "Pitch" >}}{{< /anchor >}}Pitch

## *by \[LT\]*

A first attempt at a pitch!

In developing countries, such as Nicaragua, clinics are not equipped to monitor a woman's contractions while she is labor- an important indicator of her stage of labor. Health workers currently rely on their hands- which can be time and labor intensive, especially when 8-10 women are in labor at the same time in the same room. Our innovation will give health workers the ability to monitor contraction rate and alert them to the different phased of labor.

When the woman is picked up from her home, the health worker places a band with a monitor around her wrist. Attached to it is a ball that the woman squeezes when she has a contraction. One of five signals will light on the wristband to indicate what the woman is experiencing, such as a contraction or complication that needs immediate attention and a contraction rate will display on the monitor. Especially when only one health worker is present in the ambulance truck and must drive, the visual cues will help health professionals know how to respond immediately.

[Back to top](#Labor_contraction_monitor_for_Nicaraguan_hospitals)

## {{< anchor "Re-direction" >}}{{< /anchor >}}Re-direction of our Project

After meeting with Jose for feedback on our project, we began to change directions (and revise our problem statement). Instead of working on a squeeze ball monitor alone, we're also prototyping a belt (testing various sensors) and comparing that with the squeeze ball. Ultimately, it will become a behavioral study.

### Summary of Our Meeting:

We went over what we were planning to do and Jose began to push us to try the belt idea. He's concerned that since the woman control the input with the ball, she can either be too urgent and squeeze it too many times to go to the hospital or not squeeze it enough. He encouraged us to do a behavioral study comparing the ball and belt to see the correlation or accuracy of signals (if we find the ball is just as good and even cheaper, then we go with the ball, for example). Basically he told us to explore both options. We also discussed technical details and the sensors. He thought what we were doing was…settling for too little and we could do more. He encouraged us to explore more bio sensors, homemade EMGs (suggested by Maysun), and other flexi sensors and to really talk to Professor Frey. Maybe even look at making our own sensors if we think we can make them cheaply.

We went over what the problem really was and it's actually that they don't use any monitors and need something in the hospital (not necessarily at the home to tell them when to go). The current are too expensive, so we need to make it affordable. He told us to contact Ken Endo at the biomechatronics lab, and sent us an email introducing us to some Nicaraguan contacts I think.

So:

1. Explore homemade sensors and other sensors, continue contacting people, figure out the smarts with a computer first
2. Design: make prototypes (ball and belt) and turn comp into smarts with micro controller
3. Clinical: test it out, behavioral studies

[Back to top](#Labor_contraction_monitor_for_Nicaraguan_hospitals)

1 {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "2" %}} {{% resource_link "f4a65097-6cb8-db2f-dac4-78dd84c5f5ef" "3" %}} {{% resource_link "1f285a39-6e3b-596b-f990-f46eed40d51c" "Next" %}} >>