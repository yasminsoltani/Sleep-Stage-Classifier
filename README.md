# Building a Machine Learning Model for Sleep Stage Classification 💤🛌

## Introduction
Sleep classification has been a central focus in sleep medicine since the early 20th century, with foundational efforts beginning in the 1930s when researchers first recorded and categorized brain activity during sleep using electroencephalography (EEG).

> ### But what is EEG?
> Think of it as recording your brain’s electrical signals, kind of like placing an antenna on your head to tune into your neural radio station. Different sleep stages—like light sleep, deep sleep, or REM—have distinct patterns in this brain activity, and that’s what EEG helps us capture.

But EEG is just one part of the story. In sleep clinics, doctors use something called a polysomnogram—a fancy word for a multi-sensor sleep test. It usually includes EEG (for brain waves), EOG (for eye movements), EMG (for muscle activity), and a few other signals to get a full picture of what your body is doing during sleep. It’s basically the ultimate sleep selfie. 🤳

## How does a polysomnogram look like? 
This short video-clip from Harvard Prerau Lab illustrates it perfectly:


[video](https://github.com/user-attachments/assets/7ae4106e-3a30-4a2a-a836-28436c7fba86)






> Prerau Lab, Harvard University. (n.d.). Sleep EEG Multitaper Tutorial: An Introduction to Spectral Analysis (Part 1 of 3) [Video](https://www.youtube.com/watch?v=OVsZJLtzNsw). YouTube.

Back in the 1960s, sleep scientists used machines like this one to perform polysomnography, a ***full-body recording*** of what’s going on during sleep. The setup included a series of moving pins, each one tied to a different sensor (or channel), like **EEG** for brain waves. As a person slept, these pins would scratch out rhythmic patterns on a scrolling piece of paper, creating a continuous visual record of brain activity.

After the recording, a sleep technician would sit down with a long scroll of paper covered in EEG waveforms and manually score each 30-second window by eye. They’d look for subtle shifts in frequency, amplitude, and special patterns like sleep spindles or K-complexes, all while flipping through hours of data, one tiny segment at a time.

### As you can imagine, this was incredibly time-consuming! 


![gif](https://github.com/user-attachments/assets/0362c88a-4324-4644-85f0-99f5066d48a7)


That’s why, over the years, the need to automate this process became increasingly clear. With the rise of machine learning, we now have tools that can process large EEG datasets quickly and consistently — freeing up time and enabling scalable sleep research.

### AAAAAND...

#### That's exactly what I tried to do! This project summarizes my Biomedical Engineering Senior Design Capstone Project :)




