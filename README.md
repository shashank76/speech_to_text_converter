
### Pre-requisites

- [Download and install Python](https://www.python.org/downloads/)

### Installing

After Python Installation, Install all other depepndencies.

- If you’re on Debian-based Linux (like Ubuntu) you can install with apt:
```shell
pip install SpeechRecognition
sudo apt-get install python-pyaudio python3-pyaudio
```

- For macOS:
```shell
pip install SpeechRecognition
brew install portaudio
pip install python-pyaudio
```

- If using python3 on your local machine.

```shell
pip3 install SpeechRecognition
brew install portaudio
pip3 install python3-pyaudio
```

Once you’ve got PyAudio installed, you can test the installation from the console.

```shell
python -m speech_recognition
```

For Testing the code, run server:

```shell
python speech_to_text.py
```

- If using python3 on your local machine.

```shell
python3 speech_to_text.py
```
