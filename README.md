# single-note-identification
identify single-note of piano with machine learning "CNN".

## Important
This program use "The NSynth Dataset".  
So, if you use this program, please download it from under URL site.  
<https://magenta.tensorflow.org/datasets/nsynth#license>

## Usage
1. Download train and test dataset from above URL.
2. Unpack it.
3. Exploit keyboard*.wav and move to "~/single-note-identification/data/external/train/keyboard or /test/keyboard" directory.
4. "examples.json" in train dataset renames "examples_train.json" and move to "~/single-note-identification/references".
5. "examples.json" in test dataset renames "examples_test.json" and move to there.
6. Run the programs in "~/single-note-identification/notebooks" directory in ascending order.

## About directory 
・"data" directory use to store dataset.  
・"models" directory use to store save file of model parameter.  
・"notebooks" directory use to store ".ipynb" files.  
・"references" directory use to store label data etc.  
・"reports/figures" directory use to store tensorboard files.
