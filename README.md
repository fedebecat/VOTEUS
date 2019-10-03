# VOTEUS
Voice Onset Time Enhanced User System: a web graphic interface for the analysis of plosives' release phase

# About
Voice Onset Time Enhanced User System (VOTEUS) is a tool intended to bridge the gap between the linguistic and computer science knowledge domains in the usage of [AutoVOT](https://github.com/mlml/autovot).
The goal is to provide an intuitive interface to configure and run the algorithm on large speech corpora, without requiring any computer programming skills and therefore allowing everyone to exploit all AutoVOT’s capabilities. More than that, we provide a set of functionalities that guide the user to easily generate fully annotated VOT datasets starting from raw speech recordings and their transcriptions. In particular we integrate a forced alignment routine to provide initial speech segments on which AutoVOT can be applied and we developed an intuitive interface within VOTEUS to manually refine the predicted VOT tiers, in order to produce high quality annotations.

![voteus-img](https://raw.githubusercontent.com/fedebecat/VOTEUS/master/imgs/figure_2.jpg)

VOTEUS has been conceived and developed by Duccio Piccardi and Federico Becattini

# ROADMAP
VOTEUS is currently under development for Linux and Windows operating systems and is going to be released under the MIT license, therefore allowing users to include and modify its source code within other projects. An alpha release of VOTEUS is scheduled to be released in the next months, as soon as the integration between different modules will be refined.

#### Feature development
- [x] Dataset loading (100%)
- [x] Waveform (100%)
- [x] Spectrogram (100%)
- [ ] AutoVOT
--  Backend integration (80%)
-- Frontend development (75%)
- [ ] Force alignment (30%)
- [ ] Train model
-- Backend integration (80%)
-- Frontend integration (80%)
- [ ] Refine tier (50%)
- [ ] Export (40%)
- [ ] Documentation (20%)

# Setup #

## Linux (tested on Ubuntu 16.04) ##

### Using Git ###

* Clone the repository with `git clone --recursive https://github.com/fedebecat/VOTEUS.git` (be sure to add the `--recursive` flag to clone autovot too).
* `cd autovot/autovot/code`
* `make`
