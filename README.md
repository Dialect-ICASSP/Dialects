# Leveraging Whisper ASR with LLM Fine-Tuning for End-to-End Multi-Lingual Speech Dialect Classification in Dravidian Languages

## Overview
This project is focused on addressing the speech variations caused due to regional dialects particularly in Dravidian languages such as Tamil, Malayalam, and Kannada. In our study, we created a dialected speech corpus for all three languages (not open sourced yet) and leveraged the pre-trained whisper ASR model with LLM's Fine-tuning approaches such as Low-rank Adaptation (LoRA) and Quantized-LoRA (QLoRA) for multi-class classification of dialects.

This repository contains the inforamtion about the sample audio files for each dialects from all three Dravidian languages mentioned above and contains the meta-data informations such as number of dialects per language, number of speech utterances, duration in hours and minutes and number of unique speakers, and average duration per utterance for all three langauges. The data collection process is deatiled in this figure below ![](https://raw.githubusercontent.com/Dialect-ICASSP/Dialects/main/DataCreation-Flow.png) 


# The detailed meta-data information for all three languages are given in the table below.

## Data Statistics for Tamil

| Languages | Dialects    | No. of Utterances | Duration (in hours) | Duration (in minutes) | Male Speakers | Female Speakers | Total Unique Speakers | Average Duration per Utterance |
|-----------|-------------|-------------------|----------------------|------------------------|---------------|-----------------|------------------------|----------------------------------|
| Tamil     | Chennai     | 1799              | 5.00                 | 300                    | 65            | 28              | 93                     | 10                               |
| Tamil     | Coimbatore  | 2188              | 6.08                 | 364.8                  | 15            | 6               | 21                     | 10                               |
| Tamil     | Madurai     | 2480              | 6.89                 | 413.4                  | 52            | 17              | 69                     | 10                               |
| Tamil     | Thoothukudi | 1840              | 5.11                 | 306.6                  | 68            | 34              | 102                    | 10                               |

