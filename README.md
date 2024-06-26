# openai-whisper

Example YouTube video: https://www.youtube.com/watch?v=ABQ2_znfEcg

Description:

This project provides a Python script that enables you to download a YouTube video, extract its audio and convert it to mp3 format. With the help of OpenAI Whisper, it transcribes the audio and translates the resulting Hungarian text into English.

The script uses the Pytube library to download the video, FFMPEG to extract the audio and convert it to mp3 format. OpenAI Whisper is used to transcribe the audio, and spaCy's Hungarian language model is used to split the text into individual sentences. OpenAI's GPT-3 model is then used to translate each sentence into English.

This project can be useful for those who need to quickly transcribe and translate Hungarian YouTube videos for personal or professional purposes. The resulting text can be used for subtitling, translation, or simply to get a better understanding of the content.

To use this script, you'll need to have Python 3 installed on your computer, as well as the necessary libraries mentioned above. You'll also need to have an OpenAI API key, which can be obtained from their website. Once you have these requirements, you can run the script by simply providing the URL of the YouTube video you want to transcribe and translate.

Overall, this project demonstrates the power of OpenAI's language processing capabilities and provides a useful tool for those who need to quickly transcribe and translate Hungarian videos.

# Req...

Don't forget to download the Hungarian spaCY model:

pip install https://huggingface.co/huspacy/hu_core_news_lg/resolve/main/hu_core_news_lg-any-py3-none-any.whl

Config.ini example: 

[openai]

api_key = YOUR API KEY
