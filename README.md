# Noora Health X IITK Consulting Group
![Logo](https://i.postimg.cc/VNLcvBfn/iitkconsult-cover-1.jpg)

## Handwriting recognition and Medical chatbot

This repository provides a thorough summary of the project done by IITK Consulting Group in collaboraton with Noora Health. Utilizing Google's Gemini ProVision and DocumentAI technologies, our team developed strong methods to pull tabular data from various images of paper documents. Furthermore, We developed a RAG model that can effectively answer user questions in various languages, with the help of an advanced translation interface using OpenAI.

## Project Overview:

### OCR
The repository ```Streamlit_OCR``` is for the OCR part.

#### Prerequisites

- Python version >= 3.9 installed on your local machine

#### Installation

1. Clone the repository to your local machine:
`git clone <repository_url>`
  
2. Navigate to the directory "Streamlit_OCR":
3. Install all the dependencies:
  `pip install -r requirements.txt`
4. Also install Google Cloud CLI installer from here: https://cloud.google.com/sdk/docs/install
5. The Google Cloud CLI is used for authorisation.
6. To know how to use Google Cloud CLI for verification watch this: https://www.youtube.com/watch?v=gpAiUerUdEA

### Running Locally

Follow these steps to run the project locally:

1. Make sure `gemini_chained.py` is in the same folder as `app_trial.py`.
2. Open `gemini_chained.py` and:
- Enter your API key in line 282.
- Update other details from line 17 to 20 and 263 to 265 as needed.
3. In your terminal, run the following command:
  `streamlit run app_trial.py`
  
### RAG Model 
The repository ```RAG_muodel``` is for RAG Model using the Q-A bank given to us.
 
- Final app is ```app.py```

#### Installation

For running the code first install all the dependencies by 
```
pip install -r requirements.txt
```
Then run the ```app.py``` file by running the following command on the command propmt to get a stremlit UI

```
streamlit run app.py
```
To change the Query please navigate the code in app.py and change the ```message``` variable with whatever Query you want to give in.

