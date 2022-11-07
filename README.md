# NNSVS ResF0NonAttentiveTacotron pretrained
Pretrained model for NNSVS's ResF0NonAttentiveTacotron acoustic model type\
Data used will not be shared on this repo.\
Uses [intunist](https://github.com/intunist)'s Japanese compatibility HED and dictionary included with [their Google Colab training notebook](https://github.com/intunist/notebooks/blob/main/nnsvs/intunist-nnsvs-colab.ipynb).
# Training settings (as presented in intunist's Colab notebook)
- Language - Japanese_compatibility
- Acoustic model type - ResF0NonAttentiveTacotron
- use_mdn - False
- Vibrato mode - none
- force_fix_vuv - False
- filter_long_segments - False
- sample_rate - 44100
- d4c_threshold - 0.25
- acoustic_loss - mae
- pitch_reg_weight - 0.05
# Usage
In intunist's Colab notebook, make and run a new cell like so: `!wget {link to model release}`\
Make another cell to unzip the file: `!unzip {path to model}`\
Expand the model's `exp` folder and copy+paste the path to the folder called `ResF0NonAttentiveTacotron_pretrained_intunist_prototyping_notebook` into the notebook's `pretrained_expdir` setting.
# Data
There is a total of 5 hours and 21 minutes of data used in this model.

|Singer|Minutes of data (without silence)|
|---|---|
|Ariel|68|
|アルパカ肉|6|
|ATSUYA|7|
|瓶詰め|5|
|ちかの|4|
|九|4|
|ふぇりす。|3|
|Haruqa|5|
|アトリ科ヒワ属のゲン|2|
|いろは酢|3|
|高峯いと|4|
|いつり|4|
|匿名男声|5|
|jvs001|2|
|jvs002|1|
|jvs010|1|
|jvs039|1|
|jvs076|1|
|かっぴりー|3|
|草薙快速雷虎|5|
|まいこ|4|
|MIZKI|3|
|おふとんP|4|
|紺瀬ぷち|4|
|ささささ|3|
|翠澤しのん|6|
|Suzu|104|
|Tetsu|75|
|とめあ|3|
|とろっぽ|3|
|Google Translate|20|
# Attributions
- jvs010, 039, and 076 labeled by alice
- jvs001, 002, and Google Translate labeled by Mildemelwe
- Ariel by めんるい
- Tetsu by たまご
- Suzu by ハイッヤー
- Other data is from https://github.com/oatsu-gh/enunu_kodoku_singing
- Trained on intunist's NNSVS training notebook
