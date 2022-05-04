**google-cloud-transcription** lets you use the same speech recognition technology that Google uses to transcribe your voice. If you already have an Android device, Google's Live Transcribe may be sufficient for you. If not, you have to rely on Google Docs' Voice Typing feature, which has some quirks that limit its full potential.

This script is based on [Google's sample code](https://github.com/googleapis/python-speech/blob/HEAD/samples/microphone/transcribe_streaming_mic.py)

# Setup

Place your Google Cloud Key as `google-cloud-key.json` in this folder.

Run `python transcribe_streaming_mic.py /path/to/output/file`

# Testing

Currently works on:

* macOS Monterey on Silicon