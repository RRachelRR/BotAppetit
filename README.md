HEADERIMAGE
# Bot Appetit Dataset

The Bot Appetit Dataset is a a multimodal dataset (transcripts of think-alouds, VR video recordings, object 3D coordinates) collected from 22 participants tasked with preparing a kitchen for collaboration with one of several robots in a Virtual Reality (VR) environment

*Picture showing a comparison of data recorded in dataset* 

## Data collection methodology



### Description of the data

The data is split into folders by participant id. Each participant folder contains the ego and frontal perspective videos in mp4 format for each bundle of tasks as well as a video containing all task bundles in one.

```
BotAppetitDataset/
  -P1/
    -P1_Ego_1.mp4
    -P1_Ego_2.mp4
    -...
    -P1_Ego_Complete.mp4
    -P1_Frontal_1.mp4
    -P1_Frontal_2.mp4
    -...
    -P1_Frontal_Complete.mp4
    -...
  -P2/
    -P2_Ego_1.mp4
    -P2_Ego_2.mp4
    -...
    -P2_Ego_Complete.mp4
    -P2_Frontal_1.mp4
    -P2_Frontal_2.mp4
    -...
    -P2_Frontal_Complete.mp4
    -...   
  -...
  -Annotations/
    -P1_Frontal_2.csv
    -...
  -TestFrames/
    -P1_Frontal_2/
      -01.png
      -01.txt
      -...
    -...
  -functional_part_labels.yml
  -train_test_split.yml
  -README.md
  -LICENSE.md

```

### File formats

- 189 videos in MP4 format with a total of 417 minutes of material

## Related publications

[Link]() and Bibtex for HRI paper here

## Authors

* **Rachel Ringe** - rringe@uni-bremen.de
* **Leandra Thiele** - le_th@uni-bremen.de
* **Mihai Hawkin** - mpomarlan@uni-bremen.de
* **Nima Zargham** - zargham@tzi.de
* **Robin Nolte** - nolte@uni-bremen.de
* **Lars Hurrelbrink** - lhurrelb@uni-bremen.de
* **Rainer Malaka** - malaka@tzi.de

## License

This project is licensed under the CC-BY license - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

This work was funded by the FET-Open Project #951846 [*MUHAI – Meaning and Understanding for Human-centric AI*](https://muhai.org) by the EU Pathfinder and Horizon 2020 Program.

This work has also been supported by the German Research Foundation DFG, as part of Collaborative Research Center 1320 Project-ID 329551904 [*EASE -- Everyday Activity Science and Engineering*, University of Bremen](https://www.ease-crc.org). The research was conducted in subproject *P01 – Embodied semantics for the language of action and change: Combining analysis, reasoning and simulation*
