# keras-rag-chatbot

![image](./img/screenshot.png)


Please downloaded `openchat_3.5.Q4_K_M.gguf` and `tokenizer.json` from Huggingface: 

```
download TheBloke/openchat_3.5-GGUF openchat_3.5.Q4_K_M.gguf
download openchat/openchat_3.5 tokenizer.json

Copy them to the folder ./models/openchat-3.5-gguf/
```
The downloads locate at `~/.cache/huggingface/hub/`.

and then 

```
cargo run --release
```

