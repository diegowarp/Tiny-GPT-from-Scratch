# Tiny GPT from Scratch
Simple and curious tiny GPT model trained on Tiny Shakespeare Dataset.

To develop this Tiny GPT model, I followed an incredible YouTube tutorial by [Andrej Karpathy](https://youtu.be/kCc8FmEb1nY). I also utilized important articles to apply the concepts, such as ["Attention is All You Need"](https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf) and ["Language Models are Few-Shot Learners."](https://arxiv.org/pdf/2005.14165.pdf)

For training, the [TinyShakespeare dataset](https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt) (~1115394 characters) was used, with 5000 epochs of training.

The final model had 209,729 trainable parameters and is capable of forming sentences, albeit somewhat disconnected, readable, and well-punctuated.
