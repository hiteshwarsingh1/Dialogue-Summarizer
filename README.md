#Dialogue-Summarisation
Dialogue-Summarisation using BART, T5 and supervised contrastive learning.
Used Google Colab Platform for the development process.

Pre-Trained Bart and T5 from hugging face were used. Currently only used base models due to computation restrictions. 

To learn more about SCL see https://aclanthology.org/2022.coling-1.569.pdf.

## Supervised Contrastive Learning

1. Fine-tuned pre-trained BART and T5 model to summarize a conversation based on different entity dialogues and turns.
2. Implemented Supervised Contrastive Loss to improve model’s understanding of speaker and dialogue correlation.
3. Check the performance by applying probing test on the encoder's last hidden layer for the utterance values
the summary.
* SCL Probing Code in ```SCL/SCL-Probing```. Various trained models in separate ipynb files. Run on google colab, without dependencies. 

* SCL code in standalone ipynb files with no external dependencies. 


