# Automatic-Speech-Recognition-
Built Automatic Speech Recognition (ASR) by combining a 2D Convolutional Neural Network (CNN), Recurrent Neural Network (RNN) and a Connectionist Temporal Classification (CTC) loss and evaluated the quality of model using Word Error Rate (WER). 


## Introduction

Speech recognition is an interdisciplinary subfield of computer science and computational linguistics that develops methodologies and technologies that enable the recognition and translation of spoken language into text by computers. It is also known as automatic speech recognition (ASR), computer speech recognition or speech to text (STT). It incorporates knowledge and research in the computer science, linguistics and computer engineering fields.

This demonstration shows how to combine a 2D CNN, RNN and a Connectionist Temporal Classification (CTC) loss to build an ASR. CTC is an algorithm used to train deep neural networks in speech recognition, handwriting recognition and other sequence problems. CTC is used when we don’t know how the input aligns with the output (how the characters in the transcript align to the audio). The model we create is similar to DeepSpeech2.

We will use the LJSpeech dataset from the LibriVox project. It consists of short audio clips of a single speaker reading passages from 7 non-fiction books.

We will evaluate the quality of the model using Word Error Rate (WER). WER is obtained by adding up the substitutions, insertions, and deletions that occur in a sequence of recognized words. Divide that number by the total number of words originally spoken. The result is the WER. To get the WER score you need to install the jiwer package. You can use the following command line:
