# DDSP 1.9.0: Differentiable Digital Signal Processing for Colab

Google AI [Magenta](https://magenta.tensorflow.org/) DDSP 1.9.0 for Colab, as the [original repository](https://github.com/magenta/ddsp) is focusing on [VST](https://github.com/magenta/ddsp/releases/tag/v3.1.0) that is incompatible with older models and seemingly Colab.

The purpose of this repository is to keep using old DDSP models for timbre transfer, i.e. synthesizing audio. I have not tested training new "legacy" models or other features.

```
%cd /content
!git clone https://github.com/olaviinha/ddsp.git
%cd /content/ddsp
!pip install .
```
