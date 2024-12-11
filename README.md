# Fine-tuning Google Video Vision Transformer (ViViT) using Real-life Deception Detection Dataset

[Kaggle Notebook Link](https://www.kaggle.com/code/sharooqfarzeenak/fine-tuning-google-vivit-for-deception-detection)

## About

Dataset used - [Real-life Deception Detection Dataset](https://public.websites.umich.edu/~zmohamed/resources.html)

Model Used - [ViViT (Video Vision Transformer) - Video Classifier](https://huggingface.co/google/vivit-b-16x2)

Research Paper for the dataset - [Deception Detection using Real-life Trial Data](https://web.eecs.umich.edu/~zmohamed/PDFs/Trial.ICMI.pdf)

## Use-cases

1. Assessing job interview candidates
2. Criminal proceedings, trials

# Using the model

1. Run the Kaggle Notebook
2. Model will get saved at "/kaggle/working/vivit_finetuned_deception_detection"

# Improving Accuracy

Accuracy can be improved by training with more frames per video, by increasing 'NO_OF_FRAMES' and/or 'FRAME_SAMPLE_RATE' variables, given better hardware capabilities.
