# early_lsst_classification (Final novel model name: *DeepPhotAstro*)
Repository containing code for experiments conducted with regards to early time-series classification of light curves to identify type of each astronomical source responsible for a particular light curve emissions

Required Python Packages:
1. numpy
2. pandas
3. matplotlib
4. plotly
5. seaborn
6. scikit-learn
7. tensorflow
8. keras
9. pytorch

Required linux utilities:
1. awk
2. sed
3. cut
4. gnuplot

Types of models being tested:

1. Plain RNN (using GRU-based RNN) #/plain_rnn#
2. LSTM #/lstm#
   a. Phased-LSTM
   b. Time-LSTM
3. Self-Attention (Transformer's Encoder Architecture) #/self-attention#
4. Classical ML #/classical-ml#

Benchmark models being tested against:
1. Avocado
2. RAPID

