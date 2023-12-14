# Timeseries-Energy-Data-forecasting-and-optimization

Improvement of Forecasting Methods for Real-World Applications
The idea is to achieve machine and deep learning model improvements through “in- formation sharing” between sources of information and transfer results from one specific facility to others (maybe unknown instances).
A typical problem that will be considered can be described as follows (here we are re- ferring to the problem posed by EnBW, but Gelsenwasser and Toyota are providing similar tasks):

We have generation measurements with a long history from many solar power sys- tems.
We have a relatively new solar power system and the measured generation time series is only for the previous winter.
We have used for the forecast of the new solar power plant only the data belonging to this plant. The now emerging generation peaks on sunny days will therefore be poorly predicted since the distribution to be predicted was not yet available in the training data in this way.
However, since all solar power plants are quite similar, using the information from other plants can improve the forecast.
There is a lot of literature and approaches for this general task of sharing information and transferring results.
