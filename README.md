**google-cloud-transcription** lets you use the same speech recognition technology that Google uses to transcribe your voice. If you already have an Android device, Google's Live Transcribe may be sufficient for you. If not, you have to rely on Google Docs' Voice Typing feature, which has some quirks that limit its full potential.

This script is based on [Google's sample code](https://github.com/googleapis/python-speech/blob/HEAD/samples/microphone/transcribe_streaming_mic.py), which I found from [this doc](https://cloud.google.com/speech-to-text/docs/streaming-recognize). Note: there are a couple tutorials and code samples that do the same thing, but are written differently.

# Setup

1. `brew install portaudio`
2. `pip install pyaudio`
3. If that doesn't work, try `pip install --global-option='build_ext' --global-option="-I$(brew --prefix)/include" --global-option="-L$(brew --prefix)/lib" pyaudio` ([more info](https://stackoverflow.com/questions/33513522/when-installing-pyaudio-pip-cannot-find-portaudio-h-in-usr-local-include))
4. `pip install --upgrade google-api-python-client`
5. `conda install google-cloud-speech`
6. Place your Google Cloud Key as `google-cloud-key.json` in this folder.
7. Run `python transcribe_streaming_mic.py /path/to/output/file`