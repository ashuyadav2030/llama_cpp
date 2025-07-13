# llama_cpp

First, go to this URL: https://github.com/ggml-org/llama.cpp/releases, and download the ZIP file that matches your system.

Next, download any GGUF model file (I have tested only GGUF format models).

Then, extract the ZIP file and run the following command inside the extracted folder:


llama-server.exe --model "YOUR_GGUF_MODEL_PATH" --port 10000 --ctx-size 1024

this will open a ChatGPT-like interface where you can interact with the model.

