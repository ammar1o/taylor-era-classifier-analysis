# Taylor Swift Era Classifier Analysis

## A Python ML project that categorizes Taylor Swift songs into old or new taylor using a KNN classifier with PCA dimensionality reduction and z-tests for statistical rigor.

This is the companion code to the [full deep-dive on Linkedin](LINK). Taylor Swift's 2017 song _Look What You Made Me Do_ in the album _reputation_ incudes the following spoken line:

> "I'm sorry, the old Taylor can't come to the phone right now Why? Oh, 'cause she's dead"

Logically, I had to verify this claim (ie, that the old Taylor has died) empirically through the power of data science. I use [Jake Thompson's taylor repo](https://github.com/wjakethompson/taylor/tree/main) to get a csv with every Taylor song ever along with acoustic features like "tempo", "energy", "valence", among others, from the [SoundStat API](https://soundstat.info/) to train a KNN model. The workflow is as follows:

1. Data cleaning and pre-processing
2. KNN model training
3. Exploratory z-testing to identify noisy features
4. KNN model training again
5. PCA data visualization

Here's the worfklow:

<img width="527" height="696" alt="Workflow" src="https://github.com/user-attachments/assets/f95bf246-6ae1-4b4b-adbf-d9121d6ca337" />

## How to use?

Download the Jupyter notebook and "taytay_clean" and run the code on the IDE of your choice!

## Links
- Source files: [Jake Thompson's original taylor repo](https://github.com/wjakethompson/taylor/tree/main)
- More details on methodology and results: [the Linkedin article](LINK)
