# GEHM_dataset

This repo contains the code used to produce the GEHM dataset. It was ran using Google Colab, on varying server requirement configurations (specified within the notebooks).

The user needs to specify target source video and audio destination(s) on Google Drive, which automatically attaches to the runtime after running the notebooks.

_whisper_x.ipynb_ produces PRAAT-compatible (https://www.fon.hum.uva.nl/praat/) files based on input audio. It heavily relies on [WhisperX](https://github.com/m-bain/whisperX "Whisper X Github repository") pipeline, which is based on [openAI's Whisper](https://github.com/openai/whisper "Whisper Github repository"). 

_openpose_keypoint_extraction.ipynd_ extracts OpenPose features and saves them as JSON files in separate folders.

Dataset available separately.
