# Tools and Perspectives for Interaction with Neural Audio Synthesis
## Workshop 1 - RAVE + Max/MSP

During this workshop you'll learn how [RAVE](https://github.com/acids-ircam/RAVE) and the [nn~ external](https://github.com/acids-ircam/nn_tilde) can be used together in order to perform timbre transfer and high-level manipulation on real-time audio streams.

### Train a RAVE model

If you want to train a RAVE model you [can follow those steps](https://github.com/acids-ircam/RAVE/blob/master/docs/training_setup.md) !

We also provide a colab to handle the training (it is highly recommended to have a pro account)

[![colab_badge](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1aK8K186QegnWVMAhfnFRofk_Jf7BBUxl?usp=sharing)

...unfortunately training is gonna last for days, hence [you can use those pre-trained models !](https://nubo.ircam.fr/index.php/s/rC5rt5qG8GqswEb/download)

### Setup nn~

You can [find the nn~ external here](https://github.com/acids-ircam/nn_tilde), including pre-built binaries for macos (max/msp only).

If you are using windows and max/msp you can try using [this pre-built external for max/msp](https://nubo.ircam.fr/index.php/s/34kbZEDKbYJq6cp).

If you are using PureData, you **will** need to compile it, and the windows version is not supported yet (we are open to pull request though).

### Have fun !


|                                                    RAVE x nn~                                                     |                                                   embedded RAVE                                                   |
| :---------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------: |
| [![RAVE x nn~](http://img.youtube.com/vi/dMZs04TzxUI/mqdefault.jpg)](https://www.youtube.com/watch?v=dMZs04TzxUI) | [![RAVE x nn~](http://img.youtube.com/vi/jAIRf4nGgYI/mqdefault.jpg)](https://www.youtube.com/watch?v=jAIRf4nGgYI) |