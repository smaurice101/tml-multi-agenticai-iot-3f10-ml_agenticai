Latest Logs From Latest Build
==============================

Generated On: 2025-09-26 20:31:35 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/smaurice101/raspberrypitss/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2025-09-26_20:26:40] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2025-09-26_20:26:44] STEP 2: Create topics started

  [INFO 2025-09-26_20:29:12] STEP 2: Completed

  [INFO 2025-09-26_20:29:20] STEP 3: producing data started

  [INFO 2025-09-26_20:29:23] STEP 4: Preprocessing started

  [INFO 2025-09-26_20:29:27] STEP 4: Preprocessing started

  [INFO 2025-09-26_20:29:28] STEP 3: reading local file..successfully

  [INFO 2025-09-26_20:29:33] STEP 5: Machine learning started

  [INFO 2025-09-26_20:29:34] STEP 7: Visualization started

  [INFO 2025-09-26_20:29:43] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 49689

  [INFO 2025-09-26_20:29:49] STEP 9b: Starting ollama server

  [INFO 2025-09-26_20:29:50] STEP 6: Predictions started

  [INFO 2025-09-26_20:30:03] STEP 9b: Ollama container.  Here is the run command: docker run -d -p 11434:11434 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z --env PORT=11434 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env LLAMAMODEL="llama3.1" --env mainembedding="nomic-embed-text" --env OLLAMASERVERPORT="http://127.0.0.1:11434" maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-llama3-tools, v=0

  [INFO 2025-09-26_20:30:03] STEP 9b: Success starting Agentic AI.  Here is the run command: docker run -d -p 11434:11434 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z --env PORT=11434 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env LLAMAMODEL="llama3.1" --env mainembedding="nomic-embed-text" --env OLLAMASERVERPORT="http://127.0.0.1:11434" maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-llama3-tools

  [INFO 2025-09-26_20:30:11] STEP 8: Starting docker push for: maadsdocker/tml-multi-agenticai-iot-3f10-ml_agenticai-amd64

  [ERROR 2025-09-26_20:30:25] STEP 9b: Agentic AI Step 9b DAG in tml_system_step_9b_agenticai_dag-tml-multi-agenticai-iot-3f10.py model "llama3.1" not found, try pulling it first (status code: 404)  Aborting after 10 consecutive errors.

  [INFO 2025-09-26_20:31:21] STEP 8: Docker Container created and optimized.  Will push it now.  Here is the commit command: docker commit 2676ff0e07dc maadsdocker/tml-multi-agenticai-iot-3f10-ml_agenticai-amd64 - message=0

  [INFO 2025-09-26_20:31:35] STEP 10: Started to build the documentation

  [INFO 2025-09-26_20:31:35] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


