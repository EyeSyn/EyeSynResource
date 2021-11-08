# Research Artifacts of EyeSyn
This repository contains the research artifacts for paper ["EyeSyn: Psychology-inspired Eye Movement Synthesis for Gaze-based Activity Recognition"](), which is currently under submission to IPSN'22. 

If you have any questions on this repository or the related paper, please contact **ANONYMOUS AUTHOR** via *X [DOT] Y [AT] Z*.

## **Outline**

* [Demo Video](#1)
* [Synthetic Eye Movement Dataset](#2)
* [MuseumActivity Eye Movement Dataset](#3)

## 1. <span id="1"> Demo Video</span>

A short demo video of the gaze-based museum activity recognition is shown below. The demo is running on the [Magic Leap One](https://www.magicleap.com/en-us/magic-leap-1) AR headset. The system leverages the gaze signals captured by [the onboard eye tracker](https://developer.magicleap.com/en-us/learn/guides/design-eye-gaze) in Magic Leap One to continuouly track the interactive activity the user is performing, i.e., reading the text descriptions of an exhibit or browsing the painting. Then, based on the recognized user context, they AR system adjusts the digital content that is rendered in the user's view to enhance her engagment and learning experience.

**Note: You can find the full demo video on Youtube by simply clicking the gif image below.**
[![Demo](https://github.com/EyeSyn/EyeSynResource/blob/main/demoGIF.gif)](https://youtu.be/s3GtVBg2JMg)


## 2. <span id="2"> Synthetic Eye Movement Dataset</span>


## 3. <span id="3"> MuseumActivity Eye Movement Dataset</span>
### 3.1 Data Collection Setup

We collect a gaze dataset, denoted as *MuseumActivity*. The study is approved by our institution's Institutional Review Board. Two different eye tracking devices, the [PupilLabs](https://pupil-labs.com/products/core/) and the [Magic Leap One](https://www.magicleap.com/en-us/magic-leap-1), are used in the data collection. Eight subjects (three female and five male, aged between 24 and 33) participate in the study: four subjects leverage the onboard eye tracker in the Magic Leap One, while the others use the Pupil Labs for eye movement collection. Both devices capture eye movements with the sampling frequency of 30Hz. Specifically, the subjects who are wearing the Pupil Labs are sitting in front of a 34-inch computer monitor at a distance of 50cm. The visual stimulus for each of the activities is displayed on the monitor. The resolution of the display is 800x600. We conduct the manufacturer's default on-screen five-points calibration for each of the subjects. For the Magic Leap One, the stimuli are rendered as virtual holograms placed on blank white walls around a room at head height. The holograms are with a size of 50cmx50cm in size, and their distances to the subjects are 1 to 1.5m. We perform the built-in visual calibration on the Magic Leap One for each of the subjects. 

### 3.1 Activities and Visual Stimuli used in Data Collection
For both devices, we ask the subjects to perform each of the four activities, i.e., *Read, Communicate, Browse, and Watch*, for five minutes. They can freely choose the stimuli that we have prepared:

- **Read**: we create three sets of text images from three digital reading materials that differ in both text layout and font size: a transcription of Richard Hamming’s talk on *“You and YourResearch”* [1]; a chapter from the book *“Rich Dad Poor Dad”* [2]; and achapter from the book *“Discrete Calculus”*[3]；

  [1] J. F. Kaiser, "*Richard hamming-you and your research*." Simula Research Laboratory. Springer, Berlin, Heidelberg, 2010. 37-60. 
  
  [2]  R. T. Kiyosaki and Sharon L. Lechter, "*Rich dad poor dad: What the rich teach their kids about money that the poor and the middle class do not!*", Business Plus, 2001.
  
  [3] L. J. Grady and J. R. Polimeni, "Discrete calculus: Applied analysis on graphs forcomputational science", Springer Science & Business Media, 2010

- **Communicate**: seven monologue videos are prepared, including: three video clips extracted from *an online interview withAnthony Fauci* [4]; two video clips extracted from *the ACM Turing Award Laureate interview with Raj Reddy* [5]; and *two online Youtube videos* in which the speaker is giving advice on career development [5]. All videos have only one speaker.

  [4] "Interview video with Anthony Fauci - on changing science, long COVID, and political intrusion into health agencies," [Link to the Youtube video](https://www.youtube.com/watch?v=bkoip6-yeBE).

  [5] "Interview video with Dabbala Rajagopal (Raj) Reddy," [Link to the Youtube video](https://www.youtube.com/watch?v=h99ryGYGnc0).

  [6] "Videos on career and academic resource," [Link to the Youtube video](https://www.youtube.com/playlist?list=PLnGTnWKBZrh8MvERPR_KgiANsrEmulzGO).
  
 - **Browse**: we randomly select a subset of 200 images from a public painting image dataset [7] that contains 7,937 images of famous paintings. During the data collection, for each of the subjects, we randomly select 30 images from the subset and show each of the selected images to the subject for 10 seconds.

  [7] 
