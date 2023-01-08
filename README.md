# WhisPeriment
Experimenting with the openAI Whisper model for speach to text (STT) the model is working on CPU with FP32 or GPU if available with FP16 to reduce the model memory need and be able to run it on a graphics card with only 4G of VRAM. I've added instruction to run it with CUDA or ROCm however the ROCm instructions have not been tested as I do not have the adequate hardware

This is a simple Jupyter notebook to experiment with the whisper model from OpenAi if you follow the instruction in a detailed maner it should work weather on Windows or linux. 

The notebook allow you to:
- Generate a adequate cuda environement
- Load the required python packadges
- Set:
  - The recording device for themicrophone to be used
  - The recording time
  - The speach language 
  - The model task "transcribe" or "translate" 
  - The model to be loaded

- Use a pre-recorded file or Record an audio file
- Allows to play it
- Use whisper to transcribe or translate the speach content of the audio file
