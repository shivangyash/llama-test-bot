1) First get access to use llama2 moodel by going to "https://ai.meta.com/llama/"
2) Create huggingface account with same mail as used in above
3) Create tokens by going to access tokens in your profile in hugging face.
4) Clone this repo
5) Install the requirements using - pip3 install -r requirements.txt
6) CMD - huggingface-cli login [In terminal, here give your token generated from hugging face].
7) For running we can use different models from hugging face like 7B, 13B, etc... and also GGML, GPTQ models



To use the models in different versions like: 
ORIGINAL: When you have large no. of GPU's
GPTQ: More compatible with gpu's 
GGML: Best for CPU and mac chips

### Full Precision (Original)

Llama2-7B:
```
python llama.py --model_name="meta-llama/Llama-2-7b-hf"
```
Llama2-7B-Chat:
```
python llama.py --model_name="meta-llama/Llama-2-7b-chat-hf"
```
Llama2-13B:
```
python llama.py --model_name="meta-llama/Llama-2-13b-hf"
```
Llama2-13B-Chat:
```
python llama.py --model_name="meta-llama/Llama-2-13b-chat-hf"
```
Llama2-70B:
```
python llama.py --model_name="meta-llama/Llama-2-70b-hf"
```
Llama2-70B-Chat:
```
python llama.py --model_name="meta-llama/Llama-2-70b-chat-hf"
```
### GPTQ Quantized
Llama2-7B:
```
python llama.py --model_name="TheBloke/Llama-2-7B-GPTQ"
```
Llama2-7B-Chat:
```
python llama.py --model_name="TheBloke/Llama-2-7b-Chat-GPTQ"
```
Llama2-13B:
```
python llama.py --model_name="TheBloke/Llama-2-13B-GPTQ"
```
Llama2-13B-Chat:
```
python llama.py --model_name="TheBloke/Llama-2-13B-Chat-GPTQ"
```
Llama2-70B:
```
python llama.py --model_name="TheBloke/Llama-2-70B-GPTQ"
```
Llama2-70B-Chat:
```
python llama.py --model_name="TheBloke/Llama-2-70B-Chat-GPTQ"
```
### GGML Quantized
Llama2-7B:
```
python llama.py --model_name="TheBloke/Llama-2-7B-GGML" --file_name="llama-2-7b.ggmlv3.q4_K_M.bin"
```
Llama2-7B-Chat:
```
python llama.py --model_name="TheBloke/Llama-2-7B-Chat-GGML" --file_name="llama-2-7b-chat.ggmlv3.q4_K_M.bin"
```
Llama2-13B:
```
python llama.py --model_name="TheBloke/Llama-2-13B-GGML" --file_name="llama-2-13b.ggmlv3.q4_K_M.bin"
```
Llama2-13B-Chat:
```
python llama.py --model_name="TheBloke/Llama-2-13B-Chat-GGML" --file_name="llama-2-13b-chat.ggmlv3.q4_K_M.bin"
```
