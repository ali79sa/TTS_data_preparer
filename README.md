# TTS_data_preparer
prepare data for text to speech models

According to the importance and usage of TTS models, we need data to train the models. In some languages like Persian, we don't have enough data to train the models, so I've written this code to help prepare needed data for programmers.

It takes single-speaker clear voice files without any amount of noise or music or silence and turns them into numbered audio chunk files and a related text file that contains transcriptions which are wrote using google Speech to text service.
