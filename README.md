# paperchat
## fastchat api
No gpu support, run the fastchat from gpt / qwen api
```
$ pip3 install "fschat[model_worker,webui]"  
if fail  or
$ pip3 install --use-pep517 "fschat[model_worker,webui]"
```

## fschat launch gradio web ui
``` shell
$ python3 -m fastchat.serve.gradio_web_server --controller "" --share --register configs/api_endpoints.json
```

## TODO
支持qwen api