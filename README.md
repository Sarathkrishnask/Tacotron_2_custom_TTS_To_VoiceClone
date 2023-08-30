# Tacotron_2_custom_TTS_To_VoiceClone

This program is used for converting text to speech and speech audio will be yours, let's see what steps I follow.

For this voice cloning project, I used the Tacotron 2 model with the help of the model, I trained my voice.

1. First you have to record your or which person's voice you need simply record the minimum 100 voices with good software, for this I used (audacity),
    and the audio files are saved (.wav) format.

2. Once finished above process you need to preprocess your voice, so below I gave the steps of the program I followed.
    1. batch_rename_wav.IPYNB
    2. transcribe_wav2vec.IPYNB
    3. tacotron2_preprocessor_wav_files.IPYNB
    4. audio_metadata_updater.IPYNB

3. After you finish the above programming step you, the output audio zip format, and then you have to run the Tacotron 2 model training program, and the official
    The GitHub link is given below.

   https://github.com/justinjohn0306/FakeYou-Tacotron2-Notebook

    1. FakeYou_Tacotron_2_Training.IPYNB  # FIRST YOU NEED TO TRAIN YOU VOICE USING OUTPUT ZIP FILE, ALONG YOU HAVE TO UPLOAD (list.txt) SCRIPT
    2. FakeYou_Tacotron_2_Training.ipynb  #AFTER USE THE TRAINED MODEL. JUST GIVE THE INPUT TEXT, AND IT WILL GIVE YOU THE AUDIO OUTPUT IN YOUR VOICE. 
