## Topics
---

## Automatic Speech Recognition
- The input speech is preprocessed to log-mel spectrograms and fed to ASR model and outputs are log probability of tokens of text
- general use cases include

  1.translation from speech in Language x to text in Language Y

  2.transcribing the speech in Language X to text in Language X

## Metric 'wer'
- Word error rate is the metric used to evalute speech recognition systems.
- It takes into consideration the substitutions,deletions,insertions between target text and predicted text
- It differs differently between normal text and normalized text

## My model
- The models performance can be evaluated in real time by using hugging face hosted inference api from this [link](https://huggingface.co/iammartian0/whisper-tiny-minds14)
