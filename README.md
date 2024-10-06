# Aurelian Silva

![Avatar](/image.png)

Aurelian is a proof-of-concept vocal, with only 2 minutes and 29 seconds of data in it's dataset.

## General information
- Gender: Male
- Height: 1.7m
- Weight: 600 kg
- Age: 25

## DiffSinger
A young sounding masculine vocal, with a heavy British accent. It is capable of singing in the following languages:

English (EN)
Japanese (JP)
Spanish (ES)
French (FR)
Thai (TH)

French requires the Millefeuille Phonemizer to be installed which can be found at the following site - https://utaufrance.com/comment-utiliser-diffsinger/

Thai works from the main ds-dict.yaml file so you will need to use the default DIFFS Phonemizer. It is not recommended that you edit the ds-dict.yaml for this as it is quite big and can cause your notepad application to slow down (or in my case, make NotePad++ not open at all due to it trying to open this file every time)

English, Spanish and Japanese all work without any issues in their respective phonemizers.

All languages (currently) require language tags to be prefixed onto phonemes if directly editing them, or using phoneme hints in brackets using the tags in brackets above (in lowercase).

Example of phoneme tags - The word "test" would be [en/t en/eh en/s en/t]

In English this model DOES support using [tr] [dr] [dx] and [ax] but they will need to be added manually either by editing the phonemes directly or through phoneme hints (or by using the upcoming DIFFS-EN+ phonemizer).
- Type: Diffsinger
- Languages: en, ja, fr, es, th

## Videos
[![Watch the video](https://www.youtube.com/watch?v=-wt2q_jmIz4)
