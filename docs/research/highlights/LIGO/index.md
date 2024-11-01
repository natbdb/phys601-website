# Awesome Paper

 During the summer of 2022, I participated in the  CERN Summer Student Programme, where I worked within the CMS collab
oration supervised by Drs. Maurizio Pierini and Nadezda Chernyavskaya. I contributed to their efforts
 in applying machine learning (ML) techniques to identifying gravitational wave (GW) signals at [LIGO](https://www.ligo.caltech.edu/). In particular, I built
 and evaluated transformer-based autoencoder models to detect anomalous signals in a source-agnostic manner. 
 
 This method consisted in training a model with data from the noise of the LIGO detector, a signal that the model learns to predict accurately. Running this model while the detector is operating and comparing its predicted noise signal with real data then allows us to identify "anomalies", i.e. signals that are very different than the expected noise. As it does not rely on the previous knowledge of signal shapes from specific sources, this is  a method that could extend LIGO’s reach to unknown exotic sources. 
 
 My resulting final transformer model
 performed better than a previously developed recurrent model, prompting the group to further investigate transformers. I reported my findings in this [report](https://cds.cern.ch/record/2827513).

Here is a figure from the report, showing how the machine learning model accurately predicts and reconstructs the signal from the detector:

![A screenshot of the paper](./media/ligo_screenshot.jpg)