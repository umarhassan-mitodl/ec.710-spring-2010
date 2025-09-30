---
content_type: page
description: Blog entry cataloging student progress and the final presentation for
  a group project on a non-invasive anemia diagnostic based on reflectance spectroscopy
  from the eye.
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: fd032552-908b-39df-9f46-c936d1092c8c
title: EyeHeme
uid: 50b2cdae-c3d8-7904-96ad-3dffc1b0dad5
---

_{{< anchor "Non-invasive_anemia_" >}}{{< /anchor >}}Non-invasive anemia diagnostic based on reflectance spectroscopy from the eye_

Team: Seema Kacker, and anonymous MIT students \[AJ\] and \[KK\]

This content is presented courtesy of the students and used with permission.

1 {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "2" %}} {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "Next" %}} >>

*   [Design Challenge/Problem Statement/Design Specs/Selection Matrix](#Design_Challenge)
*   [Noninvasive Anemia Diagnostic: Mission Accepted!](#Noninvasive_Anemia)
*   ["These are not your children, these are just your ideas"](#hese_are_not)
*   [Wait until you see the whites of their eyes…](#Wait_Until)
*   [Optics, Reflectance, and Confusion](#Optics__Reflectance)
*   [Grad students are awesome!](#Grad_Students)
*   [Roger, we have reflectance signal](#Roger__we_have)
*   [T minus 108 hours…](#T_Minus_108_Hours_)
*   {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "New Directions" "#New_Directions" %}}
*   {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "The Quest for a Consistent Signal" "#The_Quest_for_a_Consistent_Signal" %}}
*   {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "Team Dx presents the eyeHeme at the D-Lab Museum Showcase" "#Team_Dx_Presents" %}}
*   {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "My relationship with the eye" "#My_relationship" %}}
*   {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "Elevator Pitch" "#Elevator_Pitch" %}}
*   {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "Fact Sheet from Museum Showcase" "#Fact_Sheet_from" %}}
*   {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "Posters and Presentations" "#Posters_and_Presentations" %}}
*   {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "Biosense gets recognition" "#Biosense_Gets_Recognition" %}}

{{< anchor "Design_Challenge" >}}{{< /anchor >}}Design Challenge/Problem Statement/Design Specs/Selection Matrix
----------------------------------------------------------------------------------------------------------------

{{< resource c0026ac6-56cb-c8bb-c94e-ec976c1d9c2a >}}

### Problem or Need

Pregnant women in developing countries are often anemic and do not have an inexpensive, widespread, reliable way to diagnose the severity of their anemia. Without these diagnostics, the mother and her child are severely at risk. The most effective device in the developing world, the HemoCue, is expensive and invasive. Other methods involve some expertise in diluting solutions or matching exact colors on a colorimetry scale.One approach is to apply pulse-oximetry principles and technology to measure altered blood flow due to anemia, which is similar to an existing technology, the OrSense, in the developed world. This provides a non-invasive procedure that reduces risk of infection and increases the patient's willingness to complete the exam. We intend to create an Arduino optical blood analyzer platform that is able to, at the least, record pulse-oximetry data and anemia data. A possible modular add-on to the platform is malaria detection via magnetic principles, a non-invasive technology that is currently being researched. The platform is designed for local innovation–opening doors for new ideas to analyzing blood samples via optics or magnetism.

### Background Information

(Why do you use this equipment, what is the treatment that is sought, what does the entire process entail):

This equipment can be used any time a pulse ox or anemia diagnostic is needed. It is especially useful in the field or in ambulances, since it is portable. The device is a finger clip optical sensor, attached to a battery-powered Arduino. The sensor is clipped around the patient's finger. The SpO2 and the Hb level are printed on an LCD screen. There is also series of 3 LED lights: red (severe), yellow (mild), green (OK). One lights up based on the readings: if the patient is severely anemic, then the red light will turn on. As long as the device is on a patient's finger and turned on, it will take measurements once every thirty seconds. A one-time check can also be performed. The pulse-ox and hemoglobin functionalities can also be turned on separately.

### Technical Description/Specifications

**Readout declares:**

*   9.5 \< Hb \< 11 = mildly anemic.
*   7 \< Hb \< 9.5 = moderate anemia
*   Hb \< 7 = severe anemia. AND/OR similar using hematocrit. (Hct ~ 3 \* Hb).

Correlation value w/ established lab test, r > 0.75

Sensitivity > 80%

Specificity > 60%

\< $100 for device (could be subsidized w/ US sales)

\<$0.50 per test (average maintenance, power consumption, sterilization, etc)

### How is the Local User Community Approaching thePproblem? What Type of Improvised, or Local Solutions are Being Used?

Health posts and clinics without anemia diagnostic equipment examine patients' eyes, lips, palms, and nail beds for signs of anemia. However, this method requires training that not all medical personnel have, and only catches severe anemia. Some clinics may have WHO Hemoglobin Color Strips, but the one we visited did not. Hospitals tend to use invasive techniques that are accurate, but also time- and laboratory-intensive. Some hospitals have HemoCues, but when these break, there is no way to repair them.

### Who is the Primary Contact for this Challenge? Who are the Key Stakeholders (Do you Have Their Contact Info? If Not, Get It…)

Patricia Coffey from PATH

### What Relevant Resources are Available?

_Consider materials (not just local materials, if they are imported, then just note it. Don't get hung up in price. Cost is best defined as how difficult it is to obtain. Difficulty MAY include price, but may also be affected by other issues. Also consider resources to obtain relevant training, and frequency of supply. Use the parameter table._

Small electronics (regular LEDs, LCD screen), plastic. There are folks who know how to mess with electronics; most likely could figure out the Arduino, if they needed to fix it/change it. Nurses/doctors know how to read Hb and SpO2 measurements.

### What resources may be needed?

IR and UV LEDs, Arduino

### What are the Potential Benefits of Solving this Challenge?

More people will be diagnosed with anemia, since there is no need to wait for sterilization or an additional shipment of disposable cuvettes. This will especially help pregnant women, as anemia has been linked to both infant and maternal mortality during pregnancy. If the platform is extended, more people will also be diagnosed with malaria, which will help stop the spread of resistant malaria parasites, as well as ensuring that more victims get the treatment they need.

### What are the Potential Obstacles?

Since the device is so transparent, it may be difficult to ensure standard performance across all devices. It may also be difficult to ensure accuracy, since we are not using highly-calibrated medical equipment. Making the device battery-powered may also be unexpectedly difficult. If the device uses too much power, then batteries could be impractical. Although the device is non-invasive, it is still "looking inside of you"; patients could still be fearful or wary.

### What are the Risks of Undertaking this Project?

If the device is not specific enough, we could waste treatment on patients who are not really anemic. If it is not sensitive enough, we could deny patients the treatment they need.

### How can you Get the Local User Community Involved in the Process?

Ask for their input – is the readout confusing? Why exactly aren't there more anemia diagnoses? Is the lack of training, the lack of equipment, or invasiveness the biggest problem? We can then focus on the aspect of our device that is "most important." Also, what blood diseases are most difficult for you to diagnose (in terms of time, skill needed, etc)? These diseases would be prioritized as we extended the platform.

We could also possibly involve university students – show them how to experiment with the Arduino, and see what they come up with. H-Lab could be involved in thinking of innovative ways to use optical sensor technology. Hospital technicians could also be shown how the Arduino works, so they could repair it, or even innovate upon it, as needs arise.

### What Photographs and Videos Should you Take? (Take Them!!)

The photographs/videos of the maternity department of the hospital in Ocatal should be useful. Photos of the ambulance and current pulse-ox technology should be also.

### What Additional Information Should you Collect? (Collect It!!)

Would qualitative LED output be useful to the users? What light wavelengths do we need to measure hemoglobin? How does the magnetic malaria detector work – what components will it need to work in our platform? What other diseases can be diagnosed optically? Can all of these light sources and magnets fit onto one clip?

Problem Statement
-----------------

Anemia is a condition defined by an insufficient total volume or quantity of red blood cells, or an insufficient amount of hemoglobin in these cells. It affects nearly 2 billion people worldwide, and is associated with morbidity and mortality (WHO, 2004). Pregnant females are at an especially high risk of developing the disease – the WHO estimates that, globally, 41.8% of all pregnant women are anemic. Prevalence estimates are even higher within Africa, South-East Asia, and the Eastern Mediterranean. Maternal anemia is often caused by malaria or iron deficiency, and may result in the mortality of the mother or child, or diminished capacity and low birth weight.

This gold standard diagnostic test is an automated complete blood count (CBC), which requires a sample of blood to be drawn and reports 1. concentration of RBCs, 2. hemoglobin level, 3. "mean corpusclar volume": size of RBCs (measured by flow cytometry), and 4. RBC distribution width. Further testing may be required to determine the exact cause of the anemia (nutritional deficiency, infection, blood loss, etc.) Simple initial diagnostics may focus only on measuring the concentration of hemoglobin in a blood sample. The least invasive procedure, the HemoCue, uses a Hematocrit measurement, and requires a pinprick collection of blood. A Hemotocrit measurement employs an existing color scale that measures hemoglobin in the blood but it is expensive, requires expert lab resources, and comparison to a color chart which is often inaccurate. This is not used widely and surveys indicate that health workers and patients would be more likely to measure hemoglobin if there was a non-invasive way to do it.

One approach is to apply pulse-oximetry principles and technology to measure altered blood flow due to anemia, which is similar to an existing technology, the OrSense, in the developed world. This provides a non-invasive procedure that reduces risk of infection and increases the patient's willingness to complete the exam. We intend to create an Arduino optical blood analyzer platform that is able to, at the least, record pulse-oximetry data and anemia data. A possible modular add-on to the platform is malaria detection via magnetic principles, a non-invasive technology that is the midst of being researched. The platform is designed for local innovation–opening doors for new ideas to analyzing blood samples via optics or magnetism.[  
](#Non-invasive_anemia_)

Design Specifications
---------------------

Readout declares:

*   9.5 \< Hb \< 11 = mildly anemic.
*   7 \< Hb \< 9.5 = moderate anemia
*   Hb \< 7 = severe anemia. AND/OR similar using hematocrit. (Hct ~ 3 \* Hb).
*   Correlation value w/ established lab test, r > 0.75
*   Sensitivity > 80%
*   Specificity > 60%
*   \< $100 for device (could be subsidized w/ US sales)
*   \<$0.50 per test (average maintenance, power consumption, sterilization, etc)

Selection Matrix
----------------

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
EVALUATION CRITERIA
{{< thclose >}}
{{< thopen >}}
NOTES  
ON SPECIFICS
{{< thclose >}}
{{< thopen >}}
WEIGHTS
{{< thclose >}}
{{< thopen >}}
BASELINE: NIR  
TRANSMISSION  
(e.g., ORSENSE,  
MASIMO)
{{< thclose >}}
{{< thopen >}}
CONDUCTANCE  
(CHANGE in  
ELECTRICAL  
COUNDUCTIVITY)
{{< thclose >}}
{{< thopen >}}
REFLECTANCE  
SPECTROSCOPY
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Safety
{{< tdclose >}}
{{< tdopen >}}
Risk of infection
{{< tdclose >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Accurate
{{< tdclose >}}
{{< tdopen >}}
Sensitivity
{{< tdclose >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
0 (94%)
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Accurate
{{< tdclose >}}
{{< tdopen >}}
Specificity (1-false positive)
{{< tdclose >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
0 (78%)
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Robust
{{< tdclose >}}
{{< tdopen >}}
Can withstand extreme conditions (weather, temperature fluctuations, transportation)
{{< tdclose >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Cheap
{{< tdclose >}}
{{< tdopen >}}
Total lifetime cost (Upfront cost + per use cost)
{{< tdclose >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Maintenance / Sanitation
{{< tdclose >}}
{{< tdopen >}}
How often, how difficult it is to fix, how much effort to maintain
{{< tdclose >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Reusable
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
0.5
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Portable
{{< tdclose >}}
{{< tdopen >}}
Can travel, either with health worker or in ambulance
{{< tdclose >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Local Mfg
{{< tdclose >}}
{{< tdopen >}}
Are the parts locally attainable?
{{< tdclose >}}
{{< tdopen >}}
0.1
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Speed of Use
{{< tdclose >}}
{{< tdopen >}}
Turnaround time for patient use, how long it takes to get results
{{< tdclose >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Usability
{{< tdclose >}}
{{< tdopen >}}
How easy it is to use the device and to analyze results
{{< tdclose >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Totals (incl. weights)
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
\-2.1
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
EVALUATION CRITERIA
{{< thclose >}}
{{< thopen >}}
NOTES ON SPECIFICS
{{< thclose >}}
{{< thopen >}}
WEIGHTS
{{< thclose >}}
{{< thopen >}}
ULTRASOUND/  
OPTOACOUSTIC  
SPECTROSCOPY
{{< thclose >}}
{{< thopen >}}
SPECTRO-  
PHOTOMETRIC  
IMAGING
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Safety
{{< tdclose >}}
{{< tdopen >}}
Risk of infection
{{< tdclose >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Accurate
{{< tdclose >}}
{{< tdopen >}}
Sensitivity
{{< tdclose >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Accurate
{{< tdclose >}}
{{< tdopen >}}
Specificity (1-false positive)
{{< tdclose >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Robust
{{< tdclose >}}
{{< tdopen >}}
Can withstand extreme conditions (weather, temperature fluctuations, transportation)
{{< tdclose >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Cheap
{{< tdclose >}}
{{< tdopen >}}
Total lifetime cost (Upfront cost + per use cost)
{{< tdclose >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Maintenance / Sanitation
{{< tdclose >}}
{{< tdopen >}}
How often, how difficult it is to fix, how much effort to maintain
{{< tdclose >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Reusable
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
0.5
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Portable
{{< tdclose >}}
{{< tdopen >}}
Can travel, either with health worker or in ambulance
{{< tdclose >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Local Mfg
{{< tdclose >}}
{{< tdopen >}}
Are the parts locally attainable?
{{< tdclose >}}
{{< tdopen >}}
0.1
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Speed of Use
{{< tdclose >}}
{{< tdopen >}}
Turnaround time for patient use, how long it takes to get results
{{< tdclose >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Usability
{{< tdclose >}}
{{< tdopen >}}
How easy it is to use the device and to analyze results
{{< tdclose >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}
{{< tdopen >}}
\-1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Totals (incl. weights)
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}
{{< tdopen >}}
\-5.1
{{< tdclose >}}
{{< tdopen >}}
\-10.1
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

[Back to top](#Non-invasive_anemia_)

{{< anchor "Noninvasive_Anemia" >}}{{< /anchor >}}Noninvasive Anemia Diagnostic: Mission Accepted!
--------------------------------------------------------------------------------------------------

So what are we doing here?

Helping the lives of 41.8% of pregnant women. Saving premature and low-birth-weight babies. Reducing the dangers of birth complications. We are… diagnosing anemia – noninvasively!

In many areas of the world, invasive diagnostics are just not feasible. They cost too much, require too much training, cause too much infection, and/or are scary! A noninvasive way to diagnose anemia could save the lives of many mothers and babies – an early diagnosis would encourage a mother to go to a clinic, rather than delivering at home. A woman whose anemia cannot be detected via clinical signs would receive the iron supplements she needs.

Now… how do we do it?

[One way that's been developed (by Orsense)](http://www.orsense.com/) uses NIR transmission – very similar to a pulse ox. This is an attractive method, because you could very easily build combination pulse-ox-hemoglobin devices. This is, infact, what Orsense did. But accuracy is a problem with NIR transmission. Are there better ways to noninvasively measure hemoglobin?

[This helpful review article](http://www.clinchem.org/cgi/content/full/54/2/264) lists a few ways that noninvasive hemoglobin measurement has been explored. Electrical conductance, spectrophotometric imaging… we have no idea how these things work!! Hopefully we'll figure it out soon, so we can pick a strategy and run with it.

In the meantime….full speed ahead!

[Back to top](#Non-invasive_anemia_)

{{< anchor "hese_are_not" >}}{{< /anchor >}}"These are not Your Children, These are Just Your Ideas"
----------------------------------------------------------------------------------------------------

**Big Shift:** Diagnosing anemia via the palpebral conjunctiva (inner eyelid) instead of the finger. When we first started the project, Amit introduced us to this amazing thing called the [OrSense](http://www.orsense.com/?id=808). It's non-invasive and is "useful for hematocrit / hemoglobin determination, hidden blood loss monitoring and for anemia screening."

After watching [this product demonstration](http://www.orsense.com/?id=824), I was sold.

What could possibly go wrong with a finger? We already have a platform for a PulseOx, it would be easy. We could make a platform and make it so one could add different components in the future that involve reading blood components by measuring transmittance through the finger.

The first meeting of our team to work on Pugh charts went like this:

Me: "Let's go with the OrSense!"

Seema: "Wait, wait, wait… Don't we need to do research first? Find out more about anemia, hemoglobin, CBC (complete blood counts), hematocrit (Hct)…."

It turns out I don't like research so much. Jose mentioned two types of people in design processes:

1.  Whiteboard fillers. The people who can spend endless amounts of time filling up whiteboards with ideas upon ideas. But might not actually be good implementers.
2.  Task-oriented implementers. The people who need a recipe and can bring a design from Step 1 to 10, who will also tend to be quiet in these early stages of design.

(Mental waving of arms) That's me! The second type!

Needless to say I wasn't so warm to the idea with the eye, I wanted to start building something, anything.

It sounded like there needed to be image processing in the [review article](http://www.clinchem.org/cgi/content/full/54/2/264) (mentioned previously). Plus, people are definitely more reluctant to have doctors looking into their eyes and would much rather give their finger for testing. (My most dreaded medical treatment ever is at an optometrist's office when they test for glaucoma using air-puff tonometry).

Seema was really excited for the eye idea and kept pushing it. It has huge advantages, a thinner, mucosal layer that doesn't absorb as much as the thick subcutaneous layer of finger, therefore making it much more accurate.

Jose, Amit, Seema, and \[KK\] met up to discuss (I was to Skype® in from Wellesley), and it seemed there was a lot of excitement surrounding the diagnosing anemia through the eye. We were given an ophthalmoscope to hack, which is fantastic. So we'll see where we go from here!

So I need to let go of this finger PulseOx idea, and embrace the palpebral conjunctiva.

[Back to top](#Non-invasive_anemia_)

{{< anchor "Wait_Until" >}}{{< /anchor >}}Wait Until You See the Whites of Their Eyes…
--------------------------------------------------------------------------------------

Here's an idea: let's diagnose anemia… via the eye!

[In this review article](http://www.clinchem.org/cgi/content/full/54/2/264), we read about [using light reflectance off the inner eyelid](http://dx.doi.org/10.1117/1.2167967) to measure hemoglobin. You don't have to worry about melanin variation, and it's pretty accurate. Plus, it's new and different! Finger cuffs that measure Hb? That's been done before. But an anemia-detecting ophthalmoscope?

Now _that's_ interesting.

One lesson that's been tough to learn has been to _go step by step_. Yes, the ultimate goal is to design a device that will diagnose anemia accurately and efficiently. But that's not something we can do in three weeks. We may not even be able to measure hemoglobin in the space of three weeks! But we can make the first steps. Even if our prototype can do no more than detect a pulse, that is a huge step towards the ultimate end of detecting hemoglobin and diagnosing anemia.

Anyways, so now all we have to do is learn how optics work, how reflectance works, how an ophthalmoscope works, how blood vessels in the eye work…. and then fabricate a prototype device that puts it all together. In three weeks.

Woo hoo!

[Back to top](#Non-invasive_anemia_)

{{< anchor "Optics__Reflectance" >}}{{< /anchor >}}Optics, Reflectance, and Confusion
-------------------------------------------------------------------------------------

So we don't actually know anything about optics. We knew this before, but now we really know it. What are we actually measuring? Do we want diffuse reflectance, or the other kind? Are we looking for the wavelength, or the intensity? What kind of incident light do we want? How do we filter out the incident light, so it doesn't drown out our signal?

These are but a few of our questions. We've been emailing people left and right, but with very few replies. We finally lined up a meeting with a grad student in the [Spectroscopy Lab](http://web.mit.edu/spectroscopy/) here at MIT, so hopefully we will find some answers there.

In the meantime, we've been toying around with our difficult-to-spell ophthalmoscope. We met with the resident Expert on Everything, Dennis, who explained to us how it actually worked – light comes in the bottom, bounces off a few mirrors, and then light reflected by the patient's eye comes back into the eye of the doctor. Maybe, we thought, this could be the incident-light-filter we've been looking for! After all, the doctor isn't blinded by the light coming up from the ophthalmoscope.

We tried it with a red LED, and… nothing. We put the eyepiece of the ophthalmoscope against our light sensor, and it literally sensed zero light coming in. Can we improve the sensitivity of the sensor? Would a brighter LED help? Do we need a different sensor? The questions keep piling up. Hopefully we'll have answered enough of them to have a decent prototype next Friday…!

[Back to top](#Non-invasive_anemia_)

{{< anchor "Grad_Students" >}}{{< /anchor >}}Grad Students are Awesome!
-----------------------------------------------------------------------

Paul Yongkeun Park from the [MIT Spectroscopy Lab](http://web.mit.edu/spectroscopy/) kindly met with us last Wednesday to answer all our critical questions that were proving to be huge blocks to our prototyping.

**Big Question 1: What wavelength should our light source be and what wavelength should our detector select for? Is the reflected ray going to be at a different wavelength than our light source?**

Paul's answer: These the majority of these wavelengths are going to be the same wavelength of our light source. So really we only need to screen for the wavelength we are emitting at.

**Big Question 2: Much research in non-invasive detection of Hb used "diffuse reflectance spectroscopy", but what does this mean about what we're detecting? Many groups have used expensive fiber-optic bundles, how can we get around this for a developing world context?**

Paul's Answer: There are two types of scattering: elastic and inelastic. Inelastic scattering is a very small portion of the scattering, therefore we only need to worry about the elastic scattering. So, if we shoot a beam directly at our sample we only need to detect what is coming straight back at the detector (ie. a very small angle to the normal).

**Big Question 3: What about calibration? How can we account for the signal coming back from non-blood vessel tissue?**

Paul's Answer: Use the ophthalmoscope in the settings you are to take the measurement (ie. position away from eye, ambient light), and use a mirror instead to get a baseline reading, a certain "I0" (intensity). Then, take the real reading with the eye, intensity "I" and use the ratio "I/I0" to relate to absorbance.

Our comment: The gold standard for diagnosing anemia is drawing blood and getting the exact Hb concentration. So if we know that baseline, we can factor out the signal from the unwanted tissue.

**A Problem: How will we make sure that the signal we are getting out is from the blood vessels, the Hb? This tissue will also be reflecting back at the incident wavelength…**

{{< resource 354419f1-a8d8-b481-145b-3db936a11bad >}}

Tissue reflectance

Our response: We don't know really. Let's focus on getting a signal first, some sort of good reading.

### Potential directions for future projects:

1.  Increasing the path length of the beam in the blood vessel (ie. making the angle between the incident ray and the sample surface smaller), that would decrease the signal from the surface tissue. This would involve some sort of fixed geometry that current setup of the ophthalmoscope does not allow.
2.  Making a bigger physical detection window, so that more beams can enter, to get more signal, and therefore have a more accurate reading. We're currently limited to the small detection window of the ophthalmoscope.
3.  Using two different wavelengths to get a ratio reading, in order to make a non-invasive Pulse Ox! (This would involve two photodiodes with two filters in front.)

[Back to top](#Non-invasive_anemia_)

{{< anchor "Roger__we_have" >}}{{< /anchor >}}Roger, we have reflectance signal
-------------------------------------------------------------------------------

Yes! We love prototyping breakthroughs! Here's a nice timeline:

**Big breakthrough 1:** We decided not open up and destroy the ophthalmoscope, (even though it is fun to break things and not be able to put them back together), and decided to **place the red LED, hooked up to the Arduino, into the place where the normal halogen lamp is in the ophthalmoscope**. This makes a lot of sense because since the LED is such a diffuse light source, we were having problems collimating the light and making sure that incident light was not hitting the detector (we want the reflected light off of the sample to hit the detector). For a while we were trying to figure out ways to manipulate the light and put a physical barrier in front so that we could avoid this problem, but we forgot that we had the ophthalmoscope head, that does exactly what we want it to do! Let me explain a bit:

{{< resource 385fa09b-eefd-ee38-555d-6883e74f7bc2 >}}

Image by MIT OpenCourseWare.

So basically, the ophthalmoscope head does exactly what we want! Using a beam splitter, the mirrors inside the ophthalmoscope direct the light to the source, but the doctor does not see the light source directly, he sees the reflected rays. Instead of a doctor looking at the sample, we replace him with a photodiode.

**Big breakthrough 2: Use a filter to select for a specific wavelength.** We already have a photodiode from the Arduino PulseOx project, so we just need it to select for red light. We'll place a filter flat on the surface of the photodiode so that it can select the wavelength we want. How do we get filters for developing world contexts? Easy. We go to a florist in Wellesley and ask them for sheets of red cellophane. Wrong. Wellesley apparently doesn't have a flower arranging major. \[KK\] goes to an art supply store in Boston and they give her a perfect sheet of plastic red PBC. It's about 0.5 mm thick. It's perfect. We cut out small rectangles to fit over the photodiode. (We haven't secured it on yet).

A caveat: Our light source. Two questions:

1.  How did we pick red? We did it randomly and based off of convenience. Since we don't need a ratio like in the Pulse Ox, any wavelength should suffice to find the concentration of Hb.
2.  What about the type of light source? The original halogen lamp that the ophthalmoscope came with vs. the red LED. It does not matter since both are emitting red light. The white light has components of all light and if we filter out the other wavelengths, the photodiode will essentially be only detecting red light.

**Big Breakthrough 3: We got a reflectance reading from the ophthalmoscope!** We used the original halogen lamp, put our finger as the sample ("patient's eye"), and placed the ophthalmoscope in front of the photodiode and got some signal from the graphing program. Whoohoo!

Next new steps: Go to a butcher, get some very bloody meat, and get some sort of membrane or tube to hold the blood, and make measurements. (Of course lots of little details to figure out before then… but step by step…)

[Back to top](#Non-invasive_anemia_)

{{< anchor "T_Minus_108_Hours_" >}}{{< /anchor >}}T Minus 108 Hours…
--------------------------------------------------------------------

We have 108 hours left!

To do:

*   make a poster
*   make an elevator-pitch slide
*   construct a testing apparatus to ensure consistency as we collect data
*   go buy meat and use it to test our device
*   build a demonstration for our prototype

At this point, I'm actually pretty confident that we can do it. Er, hold on, let me go knock on some wood. As we get down to it, so much comes down to presentation. You can have a great idea, and you can have a very high-functioning prototype, but if it doesn't look good, then you're not going to get attention. I was looking at a few of the posters from the IDEAS competition earlier today, and I was surprised at how terrible some of them were! One of them didn't even state explicitly what their device did. And even though their idea was amazing, it made their project seem inferior to those with better presentation. It really brought it home for me that It's All About Selling It. As long as you have to have the idea to back it up, of course!

P.S. Inkscape is an _amazing_ tool for poster-making. And it's open source!

[Back to top](#Non-invasive_anemia_)

1 {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "2" %}} {{% resource_link f0a881e5-0cc4-23d7-a570-f619feff7140 "Next" %}} >>