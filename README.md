# Multilingual News Reader
This repository contains two Python programs that can read news from different sources in English and Hindi, respectively. Both programs use an API to fetch news articles from various news sources and read them aloud using the text-to-speech (TTS) and SAPI functionality of your operating system.

### Features
- The English News Reader program can:
  - Fetch news from various sources, such as NDTV News, WION, India Today and Livemint, among others.
  - Read aloud the headlines and summaries of the latest news articles.
  - Allow you to choose between male and female voices for the TTS output (It can be configured in program)
- The Hindi News Reader program can:
  - Fetch news from various sources, such as Dainik Bhaskar, Aaj Tak, and NDTV India, among others
  - Read aloud the headlines and summaries of the latest news articles in Hindi
  - Allow you to choose between male and female voices for the TTS output

### Prerequisites
- Python 3.x installed on your system
- Internet connectivity to fetch the news articles via API
- gTTS library installed to convert text to speech
- playsound library installed to play the TTS output
- reuqest library installed to access the URL
- jason library installed to parse the out of URL
- os library installed to remove the file

### Usage
1. Clone or download the repository to your local machine.
2. Install the required libraries listed in `requirements.txt` using pip: `pip install -r requirements.txt`
3. Run either `English_NewsReader.py` (for the English News Reader) or `Hindi_NewsReader.py` (for the Hindi News Reader) using Python: `python English_NewsReader.py` or `python Hindi_NewsReader.py`
5. Enjoy listening to the latest news articles!

### Contributions
Contributions to this repo are welcome. If you find a bug or have a suggestion for improvement, please open an issue on the repository. If you would like to make changes to the code, feel free to submit a pull request.

### Acknowledgments
This project uses the News API to fetch the news articles.
The TTS functionality is provided by the gTTS library.
The audio playback functionality is provided by the playsound library and win32com.client.
