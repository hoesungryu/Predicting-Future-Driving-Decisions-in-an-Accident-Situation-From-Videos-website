---
layout: project_page
permalink: /

title: Predicting Future Driving Decisions in an Accident Situation From Videos
authors:
    Hoe Sung Ryu$^{1}$, Uijong Ju$^{3}$, Christian Wallraven$^{1,2}$
affiliations:
    Department of Artificial Intelligence, Korea University, Seoul, Korea$^{1}$<br>
    Department of Brain and Cognitive Engineering, Korea University , Seoul, Korea$^{2}$<br>
    Department of Information Display, Kyung Hee University, Seoul, Korea$^{3}$
video: https://youtu.be/5vz4BU2W5_w/
paper: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10765283
# code: https://github.com/topics/turing-machines
# <!-- 
---

![Overview of the research framework](/static/image/overview.png)
<!-- *Figure 1: A representation of a Turing Machine. Source: [Wiki](https://en.wikipedia.org/wiki/Turing_machine).* -->

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Can human observers predict which of two directions a car will take in an accident situation when watching videos <em><strong>before the event</strong></em> recorded from the driver’s first-person perspective? And is it possible to use the observers’ eye-gaze data to predict their direction-choices? In our study with $N=30$ participants, we first show that observers identify the correct direction already from $4$ seconds(s) before the accident event with performance rising to $92\%$ at $1$s prior. Statistical analyses of the eye gaze data of the observers further identify patterns of gaze behaviors differentiating the observers’ choices. We then use an explainability approach to show that graph networks pay attention to similar scene parts as humans. Our results showcase the remarkable ability of human action predictions and that these predictions during complex, dynamic viewing can be classified from gaze data alone. 
        </div>
    </div>
</div>

---

## Problem Statement
Can humans anticipate future actions in accident situations while driving? And how are these predictions related to gaze patterns? 

## Objective
We used videos of decision-making during an accident situation during driving [1], and gathered eye-tracking data, investigating human anticipation ability and predictability from gaze 

## Significance
Our study demonstrates humans' remarkable predictive abilities in complex and dynamic situations with above chance prediction around 3 seconds before the event. Moreover, the GCN was able to decode the decisions purely from gaze data at around 4 seconds before the event.

## Reference: 
- [1] Ju et al. (2020). Acoustic cues increase situational awareness in accident situations: A VR car-driving study, IEEE transactions on intelligent transportation systems.


## Citation
```
@inproceedings{ryu2024predicting,
  title={Predicting Future Driving Decisions in an Accident Situation From Videos: A Combined Behavioral, Eye Gaze, and Computational Analysis},
  author={Ryu, Hoe Sung and Ju, Uijong and Wallraven, Christian},
  booktitle={2024 IEEE International Symposium on Mixed and Augmented Reality Adjunct (ISMAR-Adjunct)},
  pages={391--392},
  year={2024},
  organization={IEEE}
}
```
