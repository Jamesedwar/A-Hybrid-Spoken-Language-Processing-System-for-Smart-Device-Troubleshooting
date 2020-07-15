# A-Hybrid-Spoken-Language-Processing-System-for-Smart-Device-Troubleshooting
The purpose of this work is to develop a spoken language processing system for smart device
troubleshooting using human-machine interaction. This system combines a software Bidirectional
Long Short Term Memory Cell (BLSTM)-based speech recognizer and a hardware LSTM-based
language processor for Natural Language Processing (NLP) using the serial RS232 interface. Mel
Frequency Cepstral Coecient (MFCC)-based feature vectors from the speech signal are directly
input into a BLSTM network. A dropout layer is added to the BLSTM layer to reduce over-fitting and
improve robustness. The speech recognition component is a combination of an acoustic modeler,
pronunciation dictionary, and a BLSTM network for generating query text, and executes in real time
with an 81.5% Word Error Rate (WER) and average training time of 45 s. The language processor
comprises a vectorizer, lookup dictionary, key encoder, Long Short Term Memory Cell (LSTM)-based
training and prediction network, and dialogue manager, and transforms query intent to generate
response text with a processing time of 0.59 s, 5% hardware utilization, and an F1 score of 95.2%.
The proposed system has a 4.17% decrease in accuracy compared with existing systems. The existing
systems use parallel processing and high-speed cache memories to perform additional training, which
improves the accuracy. However, the performance of the language processor has a 36.7% decrease in
processing time and 50% decrease in hardware utilization, making it suitable for troubleshooting
smart devices.
