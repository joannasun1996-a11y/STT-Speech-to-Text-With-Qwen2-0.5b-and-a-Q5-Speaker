# STT-Speech-to-Text-With-Qwen2-0.5b-and-a-Q5-Speaker

```bash
# create a virtual environment
source assistant-env/bin/activate

sudo apt-get install zstd
sudo apt install curl

curl -fsSL https://ollama.com/install.sh | sh
ollama pull qwen:0.5b
