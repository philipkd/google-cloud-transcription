**google-cloud-transcription** lets you use the same speech recognition technology that Google uses to transcribe your voice. If you already have an Android device, Google's Live Transcribe may be sufficient for you. If not, you have to rely on Google Docs' Voice Typing feature, which has some quirks that limit its full potential.

This script is based on [Google's sample code](https://github.com/googleapis/python-speech/blob/HEAD/samples/microphone/transcribe_streaming_mic.py)

# Running

`export GOOGLE_APPLICATION_CREDENTIALS="YOUR_GOOGLE_CLOUD_KEY.json"`

`python transcribe_streaming_mic.py`

# Testing

Currently works on:

* macOS Monterey on Silicon