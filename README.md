# DeepRob
Learning DeepRob

# Connect to Colab with Local Runtime
[Link](https://research.google.com/colaboratory/local-runtimes.html)

```bash
jupyter serverextension enable --py jupyter_http_over_ws

jupyter notebook \
    --NotebookApp.allow_origin='https://colab.research.google.com' \
    --port=8080 \
    --NotebookApp.port_retries=0
```