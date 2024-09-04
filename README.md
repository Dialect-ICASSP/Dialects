# Leveraging Whisper ASR with LLM Fine-Tuning for End-to-End Multi-Lingual Speech Dialect Classification in Dravidian Languages

## Overview
This project addresses speech variations caused by regional dialects, specifically focusing on Dravidian languages such as Tamil, Malayalam, and Kannada. We have created a dialect-specific speech corpus for these languages (currently not open-sourced) and utilized the pre-trained Whisper ASR model. We applied advanced fine-tuning techniques, including Low-Rank Adaptation (LoRA) and Quantized-LoRA (QLoRA), for multi-class classification of dialects.

This repository provides information about sample audio files for each dialect within the aforementioned Dravidian languages. It includes metadata such as the number of dialects per language, the number of speech utterances, duration in hours and minutes, the number of unique speakers, and the average duration per utterance for each language. 

## The detailed meta-data information for all three languages are given in the tables below.

### Data Statistics for Tamil (Total unique speakers: )

| Dialects    | No. of Utterances | Duration (in hours) | Duration (in minutes) | 
|-----------|-------------|-------------------|----------------------|
| Chennai     | 1799              | 5.00                 | 300                    | 
| Coimbatore  | 2188              | 6.08                 | 364.8                  | 
| Madurai     | 2480              | 6.89                 | 413.4                  | 
| Thoothukudi | 1840              | 5.11                 | 306.6                  | 

### Data Statistics for Malayalam (Total unique speakers: )

| Dialects    | No. of Utterances | Duration (in hours) | Duration (in minutes) | 
|-----------|-------------|-------------------|----------------------|
| Kottayam     | 1879              | 5.22                 | 313.2              |
| Kozhikode  | 2490              | 6.92                 | 415.2                |
| Trivandrum     | 1001              | 3.53                 | 211.8            | 
| Thrissur | 1838              | 5.11                 | 306.6                  |   

### Data Statistics for Kannada (Total unique speakers: )

| Dialects    | No. of Utterances | Duration (in hours) | Duration (in minutes) |
|-----------|-------------|-------------------|----------------------|
| North-Kannada     | 2153              | 5.98                 | 358.8                    |  
| South-Kannada  | 1895              | 5.26                 | 315.6                  |      
| Coastal-Kannada     | 2691              | 7.47                 | 448.2                  |    
| Uttara-Kannada | 2192              | 6.09                 | 365.4                  |    

