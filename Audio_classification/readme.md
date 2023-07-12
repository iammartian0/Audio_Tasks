### 1.0
- Tried finetuning [DistilHuBERT]() on [Automatic Musical Genre Classification Of Audio Signals]() dataset but couldn't achieve the neccessary 87% accuracy.
- Played with different hyper-paremeters like
  1. batch_size
  2. gradient_accumulation_steps
  3. learning_rate
  4. weight_decay
  5. train_test data sizes
- still coundn't reach the necessary accuracy.
- The model can be tested with Hugging face hosted inference api.
follow the [link](https://huggingface.co/iammartian0/distilhubert-finetuned-gtzan)

**Conclusion** : Found that data is not sufficient enough for model, so it is overfitting on the training data

### 2.0
- Tried finetunig a complete new model [Whisper](https://huggingface.co/openai/whisper-base)  
- The model can be tested with Hugging face hosted inference api.
follow the [link](https://huggingface.co/iammartian0/whisper-base-finetuned-gtzan)

**Conclusion**: Since whisper is pretrained for Automatic Speech Recognition , even the base model encoder is strong enough to generalize well with small amount of data
