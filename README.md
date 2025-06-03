# Real-Time Image Recognition - Vintern 1B Model

## Recommended Configuration

The Vintern model is very lightweight (1B) and can run on personal computers **without requiring a GPU**. It is recommended to have a CPU with at least 8 cores and 8GB of RAM.

Refer to the original model here: [https://huggingface.co/5CD-AI/Vintern-1B-v3\_5](https://huggingface.co/5CD-AI/Vintern-1B-v3_5)

The server only needs internet access to download the model on the first run. From the second run onward, it can operate 100% **offline**.

## Setup Instructions

1. Install [llama.cpp](https://github.com/ggml-org/llama.cpp)
2. Run the command:
   `llama-server -hf ngxson/Vintern-1B-v3_5-GGUF --chat-template vicuna`
   Note: You may need to add `-ngl 99` to enable GPU support (if you are using an NVidia/AMD/Intel GPU)
   Note (2): You can also try other models [here](https://github.com/ggml-org/llama.cpp/blob/master/docs/multimodal.md)
3. Open `index.html` (or use this link: [https://github.ngxson.com/vintern-realtime-demo/](https://github.ngxson.com/vintern-realtime-demo/))
4. (Optional) Change the prompt, such as instructing it to return JSON instead of a description
5. Click "Start"

---

Let me know if you'd like this rewritten for clarity, turned into a markdown doc, or formatted for another platform (e.g. GitHub README).
