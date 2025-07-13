# Running Llama.cpp Locally with GGUF Models

Follow these steps to run a local LLM server using `llama.cpp` and a GGUF model file.

## 🧩 Step 1: Download Llama.cpp

1. Visit the official [llama.cpp releases page](https://github.com/ggml-org/llama.cpp/releases).
2. Download the ZIP file suitable for your operating system (e.g., Windows, macOS, or Linux).
3. Extract the contents of the ZIP file to any location on your system.

## 🧠 Step 2: Download a GGUF Model

1. Download any model in the `.gguf` format (e.g., from Hugging Face or other sources).
   > ✅ Note: This setup has been tested only with GGUF models.

2. Example model path:
   ```
   C:\Users\ashuy\Downloads\llama-2-7b-chat.Q5_K_M.gguf
   ```

## 🚀 Step 3: Run the Llama Server

Navigate to the extracted `llama.cpp` directory and run the following command:

```bash
llama-server.exe --model "C:\Users\ashuy\Downloads\llama-2-7b-chat.Q5_K_M.gguf" --port 10000 --ctx-size 1024
```

This will launch a local ChatGPT-like interface where you can chat with the model in your browser at:

```
http://localhost:10000
```
