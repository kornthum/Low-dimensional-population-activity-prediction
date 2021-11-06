# Low-dimensional-population-activity-prediction

**Topic:** Low dimensional population activity prediction from preparatory neuron to initiation neuron 
in motor cortex

Presentation slide: https://docs.google.com/presentation/d/13THR2DQM9AyaWgcx9Mg1xg3Da9_jEG3onY5--ek3mqo/edit?usp=sharing

FYI: The project files were not completely aggregated because we split the task and then passed the experiment or file to others. So, this repo only contains data-preprocessing and some model training experiments.

This is one of my projects from the NMA-Deep learning course together with an international team.

------------------

2 Key Question

- Can we use the preparatory neurons’ responses to predict initiation neurons’ response?
- Can the lower dimensional representation of preparatory neuron response imporve the prediction performance?

**From motor planing to Execution in Motor Cortex**
![image](https://user-images.githubusercontent.com/66479775/140597422-8ee86dcd-6a05-437d-9d35-75e32c5019df.png)

**Experiment**
![image](https://user-images.githubusercontent.com/66479775/140597433-5a218a12-760a-451b-944d-cbc755666526.png)

**Result**
![image](https://user-images.githubusercontent.com/66479775/140597441-7902d512-db2c-4492-a24a-2c834a827441.png)

![image](https://user-images.githubusercontent.com/66479775/140597449-07be0c48-d779-4106-a07b-f5c7d4e4ecfc.png)


**Conclusion**
- The model predicts the mean neuron activity.
- PCA improves the prediction a little bit, but not significant.

**Problem of the results:**
- Model only predicts the mean neuron activity.

**Possible reasons from biological perspective:**
First, the recorded neuron numbers are insufficient.
Second, we might have classified some movement initiation neurons as input, and vice verse.
