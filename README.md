# STT-Speech-to-Text-With-Qwen2-0.5b-and-a-Q5-Speaker

```bash
sudo apt install python3-venv

# create a virtual environment
python3 -m venv assistant-env
source assistant-env/bin/activate

pip install sounddevice whisper scipy numpy
pip install openai-whisper
sudo apt install espeak alsa-utils ffmpeg portaudio19-dev

curl -fsSL https://ollama.com/install.sh | sh

ollama pull qwen:0.5b
