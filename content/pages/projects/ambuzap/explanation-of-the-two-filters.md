---
content_type: page
description: Page two of a blog entry cataloging student progress and the final presentation
  for a group project on a portable low-cost defibrillator rechargeable through the
  ambulance's power.
learning_resource_types: []
ocw_type: CourseSection
parent_title: Ambuzap
parent_type: CourseSection
parent_uid: bc5c9eac-df21-936f-ac53-72945b747c52
title: Ambuzap - Page 2
uid: accd11b1-0193-bb3d-7f64-ff2b6e4efcd6
---

\<\< {{% resource_link accd11b1-0193-bb3d-7f64-ff2b6e4efcd6 "Previous" %}} {{% resource_link accd11b1-0193-bb3d-7f64-ff2b6e4efcd6 "1" %}} 2

{{< anchor "Explanation_of_the_Two_Filters" >}}{{< /anchor >}}Explanation of the Two Filters  
_by Michael Melgar_
------------------------------------------------------------------------------------------------------------------

While I was frowning over this conundrum, Divya Srinivasan discovered another super power. She built the next two pieces of the ECG signal processing circuitry: the Sallen Key filter and the Wein-Bridge notch filter. The former serves to cut off signal frequencies higher than 10 Hz (we are looking primarily for signals of frequencies ~1 Hz). However, the filter does not completely eliminate frequencies of about ~60 Hz. These are to be removed with use of the Wein-Bridge notch filter, which removes a single frequency from the signal. This will be targeted to a 60 Hz hum. While both of these have been constructed, we need to use an oscilloscope to ensure that they work correctly.

[Back to top](#Explanation_of_the_Two_Filters)

{{< anchor "Ideas_for_Signal_Visualization" >}}{{< /anchor >}}Ideas for Signal Visualization  
_by Michael Melgar_
------------------------------------------------------------------------------------------------------------------

With the internal circuitry approaching completion (knock on wood), our attention will soon turn to the method of printing the signal so that it is visible to a nurse or another health care worker. Our leading idea is to program a 'Peggy' LED board to display the signal. This would be optimal because it does not need to be restocked with paper, it consumes low amounts of power and LEDs themselves are cheap. Barring this, we could use a receipt printer to draw the waveform. This is less appealing for the reason that paper must be replaced, but it could be a lower upfront cost, making the device itself more affordable for poor clinics. We need to order the Peggy board within the next few days if we want to use it.

[Back to top](#Explanation_of_the_Two_Filters)

{{< anchor "Shock_Delivery_Details" >}}{{< /anchor >}}Shock Delivery Details
----------------------------------------------------------------------------

The portion of our project that is most novel is the specificity to the ambulance. We need to adapt a plug and outlet to each other so that they enforce the 'remains in the ambulance' objective. To work out the details of this piece, we need a 12-V battery like a car battery that would most likely be used to charge the defib/ECG. Other possible additions to the defib are 'Recharge Now' lights that switch on when the defib has spent a certain amount of time away from the ambulance and a detector to ensure the pads are being held horizontally before delivering the shock.

[Back to top](#Explanation_of_the_Two_Filters)

{{< anchor "Meeting_With_Prof._Roger_Mark" >}}{{< /anchor >}}Meeting With Prof. Roger Mark  
_by Krithika Shanmugasundaram_
---------------------------------------------------------------------------------------------------------------------------

A bit overdue, but for the sake of documentation, this wonderful progress was jumpstarted by some advice Professor Roger Mark shared with us.

After talking with him it was clear we needed to build an EKG amplifier consisting of a differential amplifier (of gain 1000). The frequency range it will be sensitive to is between 0.5 and 30 Hz. The lower end of 0.5 is 10 times higher than a diagnostic EKG, but it should be enough to inhibit motion artifact and baseline wander for our purposes of identifying V-fib.

The EKG essentially measures the potential difference between two points on the skin and we tried to see if it worked with an old EKG Prof. Mark had when we attached the electrodes to Michael's wrists. It was a faint signal, but detectable when we had a proper ground.

The challenge then becomes building an EKG that only uses two electrodes, since we only have two pads to deliver the shock that can detect the potential difference. The next step is to enable a ground in the defib, perhaps on an area of one of the shock pads, while keeping it insulated from the signal received from the other electrode.

We decided to build an amplifier rather than buy one since they are fairly expensive and out of our budget. We would need to make a circuit with three operational amplifiers (picture of circuit diagram to be posted soon). If we were to make a non-differential amplifier it should just be sure not let anything about 60 Hz go through. An easy way to filter would be with high-pass and low-pass filters, but this would not give us a defibrillator that would be able to give an accurate reading to assess VF.

A few other logistics we discussed were the materials for the electrodes and the display. Electrodes are normally silver chloride for EKGs, but stainless steel plates with a conducting jelly are more practical for a defibrillator. We discussed a few different options for the display of the wave, but the best option was to have one that showed the progression of the entire wave and then retraced it on the screen when room ran out, much like current models.

Prof. Mark advised us to talk to some professors that taught Course 6 project labs: Professor Yanik and Professor Freeman. They were contacted accordingly.

{Spidey-sense}

[Back to top](#Explanation_of_the_Two_Filters)

{{< anchor "Paul_Helped_Debug_the_Differential_Amplifier" >}}{{< /anchor >}}Paul Helped Debug the Differential Amplifier  
_by Michael Melgar_
----------------------------------------------------------------------------------------------------------------------------------------------

On Monday evening, Paul and I debugged the differential amplifier so that it now correctly subtracts the voltages at the two electrodes and multiplies the difference by 1000. It turns out the resistors I had used were placed in the wrong bin, so their resistances were 10 times less than what we'd expected. As a result, the amplifier was trying to multiply the signal by 10,000, beyond what the op amps were able to produce. As a result, the signal was just a little too large, making it extremely difficult to troubleshoot. Now, however, it works correctly and it's on to getting a signal from the electrodes and filtering the input.

[Back to top](#Explanation_of_the_Two_Filters)

{{< anchor "To_Do_List" >}}{{< /anchor >}}To Do List
----------------------------------------------------

Our current to do list consists of mostly obtaining materials and fixing the filters.

Michael met with Paul to fix the differential amplifier circuit until it finally worked! He'll most likely share his success in detail in another post. Paul seemed keen on obtaining proper signals from the electrodes. Currently there are a few options for homemade electrodes, but I am afraid they will not detect the potential differences as well as those already manufactured. We have been pestering medical for some expired ones, but they are still looking to make sure it is alright to use. Otherwise, electrode companies exist, but the prices average to $70 per pair.

Swetha's been working hard on a poster design. This is due soon, so we've been working on it, but it is difficult to predict if our project will turn out as we predict. Every day seems to change it in some way.

To do:

*   Obtain electrodes
*   Fix the filters
*   Test the system with an oscilloscope

[Back to top](#Explanation_of_the_Two_Filters)

{{< anchor "The_Longest_Yard" >}}{{< /anchor >}}The Longest Yard  
_by Krithika Shanmugasundaram_
-------------------------------------------------------------------------------------------------

The stretch leading up to Saturday night presentations was quite the journey. The components that still needed work were:

a) the diff amp

b) the filters

c) the sound mechanism

d) casing

I obtained the electrodes need from MIT medical and I also got some sheet metal (aluminum and steel) to make our own electrodes if needed.

We weren't getting a noise-free signal on the oscilloscope that looked anything like a QRS complex. The diff amp seemed to be amplifying about 3.3x rather than the 100x we were expecting. After many long hours of calculations and redoing the circuit multiple times, Michael brought the amplification up to 100. The noise on the oscilloscope had a periodic spike, which we thought would be a lot clearer if we were to filter out the noise, so the next step was to build the filters. After the filters were built, while the noise was visibly reduced, the signal had no identifiable pattern to it.

While Paul and Michael were trying to figure out what exactly was going wrong, Swetha, Divya and I worked on building a battery case that would make it easy to replace the battery inside the Defib. It was just a box made of popsicle sticks built to fit a AA battery with two steel plates on the ends soldered to the wires leading up the circuit of the camera flash.

In addition, on Wednesday, Divya and I worked to rebuild the circuit such that there were buttons for "Charge" and "Discharge" functions that act as a switch in the circuit. The charge button would complete the circuit that charges the capacitor and the discharge button, when pushed would complete the circuit allowing the capacitor to discharge through the flash.

The rest of the night on Friday was spent debugging the filters, programming the Arduino to emit the sound of the wave form detected, and building/making casing.

Once all of this was done, we put it all together. After everything seemed to be fine, we tried to address one last problem in the circuit for the flash. In the camera, there is a button in the middle of the board that the user pushes down to complete the circuit and charge the capacitor for the flash. However, this is not accessible enough for the defib device, so we put in our own switch in the circuit. Now we needed to find a way to keep this existing switch on at all times (pressed down). We thought we could use binder clips, but those did not reach par enough, so we tried to used hair barrettes (slides, if you are familiar with the lingo) and rubber band it down so that the lever mechanism of the slide would keep the switch pushed down. However, the positioning had to be very precise, and while we were testing to see if this had worked, the circuit blew on us. This meant we had to use yet another disposable camera and redo our work. However, we couldn't get the "constitutively on" switch to work in time for the museum. We'll try to get it done in time for our final presentations.

{Spidey-sense}

[Back to top](#Explanation_of_the_Two_Filters)

{{< anchor "USAID_Presentations" >}}{{< /anchor >}}USAID Presentations  
_by Krithika Shanmugasundaram_
-------------------------------------------------------------------------------------------------------

So in the half hour or so that we had before the USAID arrived, we tried to make our prototype ready for show time. Ryan helped me fix the circuit for the shock mechanism so that the flash actually worked. We angled the bobby pin a little bit more so that the lever mechanism worked then we glue-gunned everything in place. We also figured out that the block in the circuit was a loose connection the battery, so we tried to create a more secure connection to the battery in the circuit. After this, we put it all together and it worked like a charm. =)

[Back to top](#Explanation_of_the_Two_Filters)

\<\< {{% resource_link accd11b1-0193-bb3d-7f64-ff2b6e4efcd6 "Previous" %}} {{% resource_link accd11b1-0193-bb3d-7f64-ff2b6e4efcd6 "1" %}} 2