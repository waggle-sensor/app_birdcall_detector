### BirdCalls
*Owner:* Mia
*Mentors:* Sean / Nicola

#### Work Plan:
* Data preparation
* Get access to raw audio clips. (Which data? Is it already labelled?)
  * [Raw audio data](https://web.lcrc.anl.gov/public/waggle/private/training_data/aot_audio_and_images/good/dca6328534ce/audio/microphone/)  from IBP Waggle node
  * Bird Call data base
* Develop tools to extract interesting snippets from or clean up audio clips. (With what criteria?)
* Work with students to help label snippets. (Which students can help?)

#### Classification:
* Train a simple model to classify snippets. (What is the success criteria for this?)
* Experiment with generating synthetic inputs from randomly mixed snippets and various kinds of background noise.
* Integrate the synthetic inputs into the training pipeline.
*
#### Deployment:
* Integrate model into a plugin. (What values will the plugin publish?)
