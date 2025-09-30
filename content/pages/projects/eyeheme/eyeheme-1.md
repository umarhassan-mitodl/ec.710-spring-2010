---
content_type: page
description: Page two of a blog entry cataloging student progress and the final presentation
  for a group project on a non-invasive anemia diagnostic based on reflectance spectroscopy
  from the eye.
learning_resource_types: []
ocw_type: CourseSection
parent_title: EyeHeme
parent_type: CourseSection
parent_uid: 50b2cdae-c3d8-7904-96ad-3dffc1b0dad5
title: EyeHeme - Page 2
uid: f0a881e5-0cc4-23d7-a570-f619feff7140
---

\<\< {{% resource_link 50b2cdae-c3d8-7904-96ad-3dffc1b0dad5 "Previous" %}} {{% resource_link 50b2cdae-c3d8-7904-96ad-3dffc1b0dad5 "1" %}} 2

{{< anchor "New_Directions" >}}{{< /anchor >}}New Directions
------------------------------------------------------------

1) We met with Paul Hlebowitsh and found that **using the ophthalmoscope** + **LED did produce enough signal for the photodiode.** So we need to ditch that idea and come up with something else.

So the big problem was: how do we make sure we're only getting reflectance signal?

Seema suggested: Why do we need to only get the reflectance signal? We could subtract out the baseline signal from the LED and measure the change in signal…

So that's where we proceeded… and made this makeshift prototype:

{{< resource 3a2f8f09-94be-1f0e-cca3-ff03e8901ccc >}}

Prototype

So as you can see, the photodiode is right next to the LED, picking up the LED's light, but also the reflected light off of the "blood" (red paint + water) in the cuvette. (The Helping Hands were holding the cuvette securely and the Arduino board taped in place).

But then!

Seema talked with Andrew Berger from the spectroscopy lab at MIT, and he gave us a few very valuable tips:

1.  **Use a laser for prototyping purposes.** This would help us gather valid data: that we can get a different signal between blood/non-blood without worrying about other factors like diffusion of the incident light, or with problems not picking up a strong enough signal. This also eliminates the problem of getting the reflected light.
    
    In our final prototype, we may want to use lenses to collimate the light from the LED. This would be the most expensive part of the final prototype, since these lenses would cost $20-30.
    
2.  **Use milk** instead of food-colored water to simulate blood. Milk has proteins that are more comparable to blood.

[Back to top](#New_Directions)

{{< anchor "The_Quest_for_a_Consistent_Signal" >}}{{< /anchor >}}The Quest for a Consistent Signal
--------------------------------------------------------------------------------------------------

**Prototype 1:** Superbright red led + cuvettes of watered-down paint

{{< resource 8e81a760-e8c7-17fb-c883-544c67011d7c >}}

Prototype 1

We get our first exciting measurements: the red cuvette reflects much, much more than the blue! The difference in reflectance of red and blue is analogous to the difference between hemoglobin and tissue, so this was great news.

The only problem was with consistency. The difference between red and blue varied greatly… sometimes, blue inexplicably reflected more! The sensor often refused to settle on a single value, and would keep increasing or decreasing.

So after talking with a Professor Andrew Berger, we tried a different design!

**Prototype 2:** Red laser + pools of dyed milk

{{< resource 6c923762-3009-12bf-d5c2-a74c7caaba9d >}}

Prototype 2

This prototype was… painful. It was late, we were tired… and we had tape. Lots and lots of tape. Which we used. Everywhere.

The laser (suggested by Prof. Berger) gave us a little more consistency – if we shined the laser directly at the sensor, we got the same values every time. Plus, we could tell exactly where the light was going. But, it was much, much harder to keep the laser still. At first Seema just held it, but we couldn't get consistent values, so we tried aluminum foil, cardboard, ruler and clamps (shown on the left)… none of them got us consistent data.

So… we took it to D-Shop.

**Prototype 3:** Constructed setup + red laser + pool of dyed milk

{{< resource 8f081878-0f12-da51-ad0a-383810594341 >}}

Prototype 3

Thanks to D-Shop and the Wellesley chemistry labs, we have a secure set up! You can see our three samples in the back: red ("blood"), pink ("anemic blood"), and white ("tissue"). The white circles sitting in the milk represent the "eyeball". There is a hole in the middle of the setup, in which a sample tightly fits.

This seemed very promising! But, long story short, it wasn't. We got a lot of good data, but sometimes white still reflected way more than red, which was very unsettling.

We're hoping some of this inconsistency is due to the different volumes of milk that were used… if not, I have no idea what's going on!! In the meantime, for our poster, we'll have to use the data we have – there's no time to do more tests until tomorrow.

[Back to top](#New_Directions)

{{< anchor "Team_Dx_Presents" >}}{{< /anchor >}}Team Dx Presents the EyeHeme at the D-Lab Museum Showcase
---------------------------------------------------------------------------------------------------------

Yesterday we presented our eyeHeme, which is the "hip" name I came up with and I guess other people liked as well. Amit suggested using a hip name instead of a more standard name.. so there we are!

It was a great time to see the devices that all the other D-lab classes came up with. Really interesting stuff…

Seema gave an awesome elevator pitch, and in general people seemed really interested in our device. Our device is different from other teams in that it's solving worldwide, huge, very apparent need. The other projects have a lot of potential to solve problems of poverty. They identified a problem they observed in the field, and are solving it, but it seems that it will only affect a select group of people. So, this is probably the eyeHeme's strength, that we have potential to affect 2 billion people, 42% of pregnant women around the world, 40-50% of children in developing countries…

We also had someone run up to us as we were cleaning up named Sarah Bird, who is the Chief Technology Officer at IRD (Interactive Research and Development), a medical devices organization in Pakistan. She was really excited about our project and offered to help us set up some clinical trials when we had a patient-ready device built. Very nice!

[Back to top](#New_Directions)

{{< anchor "My_relationship" >}}{{< /anchor >}}My Relationship With the Eye
---------------------------------------------------------------------------

Hey everyone – I'm new to the blogging thing, but I'll do my best to keep up with my awesome team members!

I wanted to write a bit about my relationship with the eye. As \[AJ\] mentioned in one of her earlier posts, I was really into this idea of obtaining a signal from the eye instead of other tissue. Why?

*   Using the eye as a target is the really novel aspect of our project (assuming we get it to work). Obtaining absorbance signals from tissue-based measurements is already pretty common (think Orsense, Pulse-Ox, etc.) Furthermore, as we've been reading the literature, we've found a number of other groups are **currently** attempting to develop optical diagnostics based on the eye. As noted in [Jay, et al., 2007](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4352943&userType=&tag=1), physicians and other providers already qualitatively study pallor of the eye for anemia diagnosis. The challenge is to develop a more quantitative technique that can be used as an initial screen for anemia.

Evidence for diagnostic potential:

*   Mucosal surface, less tissue to absorb light, less scattering of light

The eyes are affected by several conditions stemming from other parts of the body (from The Merck Manual's "[Diseases of the Eye](http://www.merckmanuals.com/home/sec20/ch225/ch225b.html)"). This all suggests that the eye may already be a familiar target for informal/qualitative diagnoses (so our diagnostic may be easily integrated into current practice), and that tools may already exist to better visualize parts of the eye.

*   Vision loss can be caused by: diabetes, macular degeneration, injuries, some infections, ischemic attack/mini-stroke, etc.
*   Double vision may be caused by: fatigue, alcohol intoxication, multiple sclerosis, and injury, as well as by a serious disorder of the brain or nervous system, such as a tumor, aneurysm, or stroke.
*   The appearance of the eye may change (redness/swelling, etc.) due to inflammation, allergies, or other bacterial infections
*   Pupil size can be affected by syphilis
*   Jaundice causes the sclera to become yellow
*   The eyelids may droop (ptosis) as a result of myasthenia gravis and disorders that cause nerve damage
*   A thyroid disorder, Graves' disease, can cause the eyes to appear unusually wide open and prominent, because they are being pushed forward (exophthalmos).
*   Eye dryness may be caused by vitamin A deficiency or Sjögren's syndrome

Extraneous Personal background:

*   I like eyes. Aside from serving as a rich medical diagnostic tool, a person's eyes are a medium for emotional expression. Haven't you ever seen someone’s eyes smile?
*   I'm not very good at drawing in general, but I remember that when I was about 11, I took an art class over the summer and managed to get through it by drawing eyes for most of my projects. The toughest part was trying to make each eye in a pair compatible with the other, but I managed to escape this by drawing only one in some more…abstract form.
*   Some people are taken back by any sort of touching of the eye, but I've been comfortable with it from a young age. I think I first started wearing glasses in 2{{< sup "nd" >}} grade, and I've had contacts since middle school. My vision is terrible (about -8.0 in both eyes) and I've spent a large amount of time and money on diagnostic eye exams, prescription lens fittings, treatment for eye ulcers, etc. And because my brother also has terrible vision and when we were younger I went along with him to eye exams and our doctor allowed me to peer into her ophthalmoscope, I've been able to gain an appreciation for the complexity and elegance of this organ.

Please note that I do not prescribe to alternative medicine techniques like "eyelogy" or "iridology" or "scelerology." My impression is that although the eye can be a very useful tool for some diagnostic purposes, these fields are generally accepted as bogus.

[Back to top](#New_Directions)

{{< anchor "Elevator_Pitch" >}}{{< /anchor >}}Elevator Pitch
------------------------------------------------------------

Over the weekend at the D-Lab showcase event, I represented our team by giving an elevator pitch on the eyeHeme. Each team (from every D-Lab class) gave a quick presentation on their device, inviting the audience to come visit their poster to learn more. I wrote up something while thinking about what to say, although I ended up just informally mentioning some main points. Below is the formal, written version:

Anemia is a condition characterized by red blood cells that do not supply an adequate amount of oxygen to tissues in the body. This affects an estimated 2 billion people worldwide, and is associated with decreased productivity, increased risk of infection, and rapid disease progression. The WHO describes anemia as a leading contributor to the global burden of disease, and the World Bank estimates that, worldwide, $50 billion in GDP is lost each year due to anemia.

Pregnant women and young children are at especially high risk, and maternal anemia is associated with maternal and infant morbidity and mortality.

Effective treatment for most anemia cases is well-understood, but especially in developing world contexts, anemia remains underdiagnosed and undertreated. Current diagnostic methods – generally using analysis of a blood sample – are invasive and costly, and often require additional skilled labor and infrastructure for sample analysis, infection control, and waste management. Non-invasive techniques –mostly based on observation – are criticized as qualitative and inaccurate, and are only sensitive enough to detect severe cases. A significant bottleneck in addressing the worldwide challenge of anemia is the lack of an appropriate and effective diagnostic.

So we ask you now to envision the eyeHeme, our novel non-invasive system used to diagnose anemia. Our design uses reflectance from blood vasculature in the inner eyelid to measure the concentration of hemoglobin, the iron-containing compound of RBCs that carries oxygen. This region is a highly vascular area, and an excellent target for an optical detection device. Specifically, it is not affected by scattering in thick tissue or variation in melanin – two challenges that other attempted optics-based diagnostic devices have faced. We believe that the reflectance signal we detect is both sensitive and specific enough to serve as an initial screen for anemia. We welcome your comments and feedback – please come see our table upstairs. Thank you.

[Back to top](#New_Directions)

{{< anchor "Fact_Sheet_from" >}}{{< /anchor >}}Fact Sheet from Museum Showcase
------------------------------------------------------------------------------

Anemia FactSheet

**Definition:**

Anemia is a condition defined by the inability of red blood cells (RBCs) to carry enough oxygen to the tissues of the body.

This can involve:

1.  An insufficient number of RBCs (low production and/or high destruction)
2.  An insufficient amount of hemoglobin, the iron-rich protein in RBCs that carries oxygen
3.  An insufficient size of the RBCs

**Common Causes:**

1.  Insufficient RBC production due to inadequate intake or poor utilization of dietary iron (due to poor diet and helminth infections) – >50% of anemia cases
2.  Excessive RBC destruction due to malaria, which displaces hemoglobin and prevents the transport of oxygen to the tissues
3.  Excessive RBC loss due to helminth infections (mainly hookworm and schistosomiasis and in some cases trichuriasis) leading to iron deficiency
4.  Excessive blood loss in women during their reproductive years

**Impact:**

*   An estimated 2 billion people worldwide are anemic
*   Pregnant women and young children are at especially high risk
*   Anemia is estimated to contribute to 20% of maternal deaths
*   42% of all pregnant women worldwide are anemic
*   40-50% of preschool children in the developing world are anemic
*   Nine out of ten anemics live in the developing world, but anemia affects all countries and demographics
*   A leading cause of global burden of disease, associated with severe morbidity, mortality, and birth complications
*   Substantial Economic Impact (lost productivity, lost life)

{{< resource 474632db-22c4-4040-aed4-e7e87def2fd7 >}}

Courtesy of The World Bank. Used with permission.

{{< resource fe538802-3999-0477-411b-13cecd91ed12 >}}

Courtesy of The World Bank. Used with permission.

**Effects:**

*   Associated with fatigue, weakness, dizziness and drowsiness
*   Underlying cause of chronic ill health, increased risk of infection and mortality
*   Associated with more rapid progression of heart and kidney diseases
*   Maternal anemia:
    *   Impaired fetal development during pregnancy
    *   Maternal mortality from cardiac failure and shock
    *   Perinatal and infant morbidity and mortality
*   Delayed cognitive development
*   Reduced physical capacity

**Interventions/Treatment:**

*   Iron supplements targeted to at-risk groups
*   Fortification of staple foods with iron and other micronutrients that cause anemia for the general population and iron-fortified foods targeted to at-risk groups
*   Prevent and treat malaria
*   Use of insecticide-treated materials and bed nets, particularly by at-risk groups, to prevent anemia
*   Deworming (anthelminthics) in at-risk groups

{{< resource 050a2f3c-a805-561a-9078-de0726b4f2bd >}}

Courtesy of the World Health Organization. Used with permission. For complete publication, see de Benoist, Bruno, Erin McLean, Ines Egli, and Mary Cogswell, eds. "Worldwide Prevalence of Anaemia 1993-2005: WHO Global Database on Anaemia." Geneva, Switzerland: WHO Press, 2008.

Reference: [http://www.who.int/topics/anaemia/en/](http://www.who.int/topics/anaemia/en/)

**Diagnosis:**

*   US: Complete Blood Count (CBC)
*   Hemoglobin concentration
*   Hematocrit: the amount of space the RBCs occupy in the blood
*   Number of RBCs, WBCs, platelets
*   Mean Corpuscular Volume (MCV): average size of RBCs

Obvious changes in the palpebral conjunctiva → useful for diagnostic purposes?

{{< resource 54ae5249-f856-a245-ac67-c3e480ca8218 >}}

Courtesy of Society of Photo Optical Instrumentation Engineers. Used with permission. For complete article, see McCurdy, John W. et al. "Diffuse Reflectance Spectra of the Palpebral Conjunctiva and its Utility as a Noninvasive Indicator of Total Hemoglobin." _Journal of Biomedical Optics_ 11, no. 1 (2006): 014019.

[Back to top](#New_Directions)

{{< anchor "Posters_and_Presentations" >}}{{< /anchor >}}Posters and Presentations
----------------------------------------------------------------------------------

(Poster and presentation files removed due to copyright restrictions.)

We also got invited to present at the The World Health Medical Technology Conference at BU this Monday! There are some really exciting presentations during the day. I'm bummed I can't go…

[Back to top](#New_Directions)

{{< anchor "Biosense_Gets_Recognition" >}}{{< /anchor >}}Biosense Gets Recognition
----------------------------------------------------------------------------------

Mary Xu, in our D-Lab class sent us a link about [Biosense](https://sites.google.com/site/biosenseglobal/blogposts/biosenseisinthefinalrunfortheprestigiousechoinggreenfellowship), a non-invasive anemia screening that is an Echoing Green Fellow receiving up to $90,000 in seed funding and technical support.

\[KK\] had gotten in contact with them as well and they were willing to meet up with us in Seattle or New York, but I guess we didn't get the chance.

Take a look at Biosense, with their product [ToucHb](http://www.biosense.in/). ToucHb uses a modified pulse-oximeter using the finger as a measuring point for hemoglobin. It looks like they had gone to clinical trials this past January. It would be interesting to see the results of their clinical trials and how accurate their readings were considering the same problems we faced about subcutaneous tissue being different in each person, thus affecting the Hb readings.

But congrats to Biosense for drawing more attention to the worldwide anemia problem!

[Back to top](#New_Directions)

\<\< {{% resource_link 50b2cdae-c3d8-7904-96ad-3dffc1b0dad5 "Previous" %}} {{% resource_link 50b2cdae-c3d8-7904-96ad-3dffc1b0dad5 "1" %}} 2