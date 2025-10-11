Latest Logs From Latest Build
==============================

Generated On: 2025-10-11 14:10:43 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/smaurice101/raspberrypitss/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2025-10-11_14:05:12] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2025-10-11_14:05:15] STEP 2: Create topics started

  [INFO 2025-10-11_14:07:30] STEP 2: Completed

  [INFO 2025-10-11_14:07:38] STEP 3: producing data started

  [INFO 2025-10-11_14:07:41] STEP 4: Preprocessing started

  [INFO 2025-10-11_14:07:46] STEP 3: reading local file..successfully

  [INFO 2025-10-11_14:07:50] STEP 4: Preprocessing started

  [INFO 2025-10-11_14:07:53] STEP 6: Predictions started

  [INFO 2025-10-11_14:07:53] STEP 7: Visualization started

  [INFO 2025-10-11_14:07:57] STEP 5: Machine learning started

  [INFO 2025-10-11_14:08:12] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 49689

  [INFO 2025-10-11_14:08:17] STEP 9b: Starting ollama server

  [WARN 2025-10-11_14:08:28] STEP 9b: There seems to be an issue starting the Ollama container.  Here is the run command - try to run it nanually for testing: docker run -d -p 11434:11434 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z -v /mnt/c/maads/tml-airflow/rawdata/ollama:/root/.ollama:z --env OLLAMA_LOAD_TIMEOUT=30m0s --env PORT=11434 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env LLAMAMODEL="qwen2.5:3b && qwen2.5:3b && llama3.2:3b" --env mainembedding="nomic-embed-text" --env OLLAMASERVERPORT="http://127.0.0.1:11434" maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-llama3-tools

  [INFO 2025-10-11_14:08:38] STEP 8: Starting docker push for: maadsdocker/tml-multi-agenticai-iot-3f10-ml_agenticai-amd64

  [INFO 2025-10-11_14:10:13] STEP 8: Docker Container created and optimized.  Will push it now.  Here is the commit command: docker commit dd7b0be93b78 maadsdocker/tml-multi-agenticai-iot-3f10-ml_agenticai-amd64 - message=0

  [INFO 2025-10-11_14:10:43] STEP 10: Started to build the documentation

  [INFO 2025-10-11_14:10:44] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


