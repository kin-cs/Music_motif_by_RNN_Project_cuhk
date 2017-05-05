# MMRNN
MMRNN (Music Motif generator Recurrent Neuron Network) is a music generator which you can input your song into this model
and get the short piece of generated music from the model. You can create your own music based on the generated music as a motif.

At first, I made this model for my Deep Learning course in CUHK.

### Dependancies
- Music21
- Tensorflow
- Keras
- numpy
- matplotlib
You need Jupyter notebook to open the file.

## Procedure
### Train for model
1. Run LSTM_Model_500_Generator.ipynb by Jupyter notebook
2. in Preprocessing, change the path to import your own file
3. in Preprocessing, Change the melody track number to the one you want to change (in # take the melody track)
4. in Preprocessing, change the melody back to C for having a easier view afterward.
5. Take a look of your input song by using .plot('PlotHorizontalBarPitchSpaceOffset', title='MyTitle') function
6. Stripped off the part you think that is redundant.
7. Ready to train!

### Training time for this model
It takes around 2-3 hours to train in this deep model on AWS p2.xlarge (1 GPU).
