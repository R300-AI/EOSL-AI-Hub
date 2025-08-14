## MediaTek Genio Series
  
  | Model            |  Chipsets  |    Framework          |    Speed (token/s)<br><sub>Prompt/Eval |   Memory (GB) |  Power (Watt) |     Temp (°C)    |
  |------------------|------------|-----------------------|--------------------|---------------|---------------|------------------|
  | deepseek-r1:1.5b |  Genio-510 | Ollama(`Cortex-A78`)   |   9.76/ 5.86      | 4GB (100%)    |               |                  |
  | llama3.2:1b      |  Genio-510 | Ollama(`Cortex-A78`)   |   21.06/ 6.44     | 4GB (100%)    |               |                  |
  | qwen2.5:0.5b     |  Genio-1200 | Ollama(`Cortex-A78`)       |        /          |               |               |                  |
  | qwen2.5:1.5b     |  Genio-1200 | Ollama(`Cortex-A78`)       |        /          |               |               |                  |
  | phi-2:0.5b       |  Genio-1200 | Ollama(`Cortex-A78`)       |        /          |               |               |                  |

## AMD Ryzen AI 300 Series



  | Model            |       Chipsets      |    Framework   |  CPU (%) | GPU (%) | NPU (%) | Memory (GB) |  Time-to-first-Token (TTFT) |  Speed (token/s)  |
  |------------------|---------------------|----------------|----------|---------|---------|-------------|-----------------------------|-------------------|
  | qwen2.5:1.5b     |  Ryzen AI 9 HX 375  | Ollama(`VGM`)  |  15      |   3     |   0     |  3.8 (12%)  | 697.10 / 50.15              |                   |
  | llama3.2:1b      |  Ryzen AI 9 HX 375  | Ollama(cpu:40%,GPU:2%)   |   340.67/ 42.75     | 4.2GB (14%)   |               |                  |
  | deepseek-r1:1.5b |  Ryzen AI 9 HX 375  | Ollama(cpu:20%,GPU:1%)   |    110.82/49.21     | 3.8GB (12%)           |               |                  |
  | qwen3:1.7b       |  Ryzen AI 9 HX 375  | Ollama(CPU:18%,gpu:2%)   |    121.48/42.00     |               |               |                  |
