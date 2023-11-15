# DDSP 1.9.0: Differentiable Digital Signal Processing for Colab

Google AI [Magenta](https://magenta.tensorflow.org/) DDSP 1.9.0 for Colab, as the [original repository](https://github.com/magenta/ddsp) is focusing on [VST](https://github.com/magenta/ddsp/releases/tag/v3.1.0) that is incompatible with older models and seemingly Colab.

FYI: I have not tested training new models with this repo. Synthesizing audio using old models works great.

```
%cd /content
!git clone https://github.com/olaviinha/ddsp.git
%cd /content/ddsp
!pip install .
```
