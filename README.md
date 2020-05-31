# deepspeech-basics
I am creating this project to learn about [Baidu's DeepSpeech](https://arxiv.org/abs/1412.5567) and its implementation by Mozilla.


The jupyter notebook covers how to setup a Google Colab environment for **Mozilla's implmentation of DeepSpeech 0.6.1**:

Setup steps:
  * install `git lfs`
  * download the DeepSpeech model as described in the [release notes](https://github.com/mozilla/DeepSpeech/releases/tag/v0.6.1)
  * download the checkpoint file
  * download the sample audio files
  * clone [Mozilla's DeepSpeech git repo](https://github.com/mozilla/DeepSpeech)
  * `pip install deepspeech`
  * `pip install -r requirements.txt`
  
The notebook continues on with: 
  * running a transcription example from [Mozilla's docs](https://deepspeech.readthedocs.io/en/v0.6.1/).
  * running a training example from Mozilla's docs.
  
And finishes with an attempt to train a new network to recognise a complex word such as the name of an antibiotic.
