# Analyzing_public_sentiments_to_data_center_energy_consumption

__!!! As the paper is under review, all contents in this repository currently are not allowed to be re-used by anyone until this announcement is deleted.__

## 0. Summary of supplemental materials
This table below shows all supplemental materials. All sheets in Tables S1, S2, and S3  are arranged in the order shown in this table.


## 1. Introduction
### 1.1 Objective 
This repository aims at providing the codes and data regarding the paper entitled “……” for the public, and it is developed by XXX University of XXX in Singapore and XXX University in China.
### 1.2 Acknowledgements
We greatly appreciate the selfless spirits of these voluntary contributors of a series of open python libraries, including Ollama (https://github.com/ollama/ollama), meta-llama (https://github.com/meta-llama/llama), google-gemini (https://github.com/google-gemini/gemma-cookbook), some base works (https://github.com/Data4Democracy/media-crawler, https://github.com/jeffreyxchan/Twitter-Crawler), and so on. Our work stands on the shoulders of these giants.
### 1.3 Copyright
As for anything regarding the copyright, please refer to the MIT License or contact the authors.


## 2 Reuse ths repository
### 2.1 Set environment
All codes are developed on Python 3.9, and the IDE adopted is PyCharm. The hardwares for running these codes are as follows.

![image](https://github.com/user-attachments/assets/8df90782-f33a-4bc9-abda-2b144687c5ad)

Before submitting these codes to Github, all of them have been tested to be well-performed (as shown in the screwshots). Even so, we are not able to guarantee their operation in other computing environments due to the differences in the python version, computer operating system, and adopted hardware.

### 2.2 Mine posts and comments from twitter


↑↑↑ A video to showcase the data mining from Twitter.


↑↑↑ All codes could be found below


### 2.3 Sentiment labeling by Gemma 2, Llama 3.2 & Phi 3

https://github.com/user-attachments/assets/c1b962a8-b48f-4cad-81e0-ee718074758b

↑↑↑ A video to showcase the sentiment labeling process based on Llama 3.2.

![image](https://github.com/user-attachments/assets/33d14148-2bc8-4650-8364-210fd6dff7ff)

↑↑↑ All codes could be found above

### 2.4 Compare the performance of Gemma 2, Llama 3.2 & Phi 3 in sentiment labeling

![Screenshot of F1-score of gemma 2](https://github.com/user-attachments/assets/9fa4caaf-7295-4a39-b756-5217f694b245)
![Screenshot of F1-score of llama 3 2](https://github.com/user-attachments/assets/a507e110-36fe-4194-9795-036d11cf9f6a)
![Screenshot of F1-score of phi 3](https://github.com/user-attachments/assets/2a881520-0bf7-449f-867c-864417e3fea9)

↑↑↑ Screenshots of the Precision, Recall, and F1-score of Gemma 2, Llama 3.2, and Phi 3.

![image](https://github.com/user-attachments/assets/acaaf867-c41f-4942-a1af-e37ee753e844)

↑↑↑ Codes for calculating the Precision, Recall and F1-score could be found above


### 2.5 Topic labeling by Gemma 2

3.4.1 Topic prompts

![image](https://github.com/user-attachments/assets/3cd49eb7-4ff3-4a92-ad5c-61d4e3355d33)

↑↑↑ Positive topic prompt for LLMs in topic classification.

![image](https://github.com/user-attachments/assets/a06d2ce2-f0ac-4e5e-9049-3e7c4eaa99ce)

↑↑↑ Negative topic prompt for LLMs in topic classification.

3.4.2 Topic labeling

![positive topic](https://github.com/user-attachments/assets/1f4cb64c-93f1-4295-b3bc-ea47f5db8876)

↑↑↑ Positive topic classification based on Gemma2.

![11月9日 (1)](https://github.com/user-attachments/assets/1d0142a9-de5c-4891-8266-a053700bd105)

↑↑↑ Negative topic classification based on Gemma2.

↓↓↓ Codes for positive and negative topic labeling could be found below

![image](https://github.com/user-attachments/assets/9c8139dc-07ca-49b9-974c-7b171c0f5c19)


