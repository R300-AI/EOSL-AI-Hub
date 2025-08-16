## MediaTek Genio Series
  
  | Model            |  Chipsets  |    Framework          |    Speed (token/s)<br><sub>Prompt/Eval |   Memory (GB) |  Power (Watt) |     Temp (°C)    |
  |------------------|------------|-----------------------|--------------------|---------------|---------------|------------------|
  | deepseek-r1:1.5b |  Genio-510 | Ollama(`Cortex-A78`)   |   9.76/ 5.86      | 4GB (100%)    |               |                  |
  | llama3.2:1b      |  Genio-510 | Ollama(`Cortex-A78`)   |   21.06/ 6.44     | 4GB (100%)    |               |                  |

## AMD Ryzen AI 300 Series

`VGM`是Ryzen AI獨有的記憶體最佳化技術

> * **TTFT**：Time-to-first-Token

### Ryzen AI 9 HX
  | Model                        |  Chipsets  |  Framework  |  CPU (%) | GPU (%) | NPU (%) |  TTFTn (ms) |  Speed (token/s)  |
  |------------------------------|------------|-------------|----------|---------|---------|--------------|------------|
  | qwen2.5:latest               | 9 HX 375 | Ollama        |    34    |    4    |    0    |       676.5   |  11.26     |
  | qwen2.5:0.5b-base-q2_K       | 9 HX 375 | Ollama        |    33    |   10    |    0    |        17.6   | 108.76     |
  | qwen2.5:0.5b-base-q3_K_S     | 9 HX 375 | Ollama        |    37    |   12    |    0    |        21.0   | 104.98     |
  | qwen2.5:0.5b-base-q3_K_M     | 9 HX 375 | Ollama        |    45    |   11    |    0    |         20.6  | 102.63     |  
  | qwen2.5:0.5b-base-q3_K_L     | 9 HX 375 | Ollama        |    38    |   12    |    0    |        20.5   | 105.15     |
  | qwen2.5:0.5b-base-q4_0       | 9 HX 375 | Ollama        |    32    |   15    |    0    |        21.6   |  99.54     |
  | qwen2.5:0.5b-base-q4_1       | 9 HX 375 | Ollama        |    33    |   10    |    0    |        26.0   |  99.45     |
  | qwen2.5:0.5b-base-q4_K_S     | 9 HX 375 | Ollama        |    30    |    7    |    0    |         18.8  | 112.33     |
  | qwen2.5:0.5b-base-q4_K_M     | 9 HX 375 | Ollama        |    38    |   13    |    0    |        19.0   |  96.10     |
  | qwen2.5:0.5b-base-q5_0       | 9 HX 375 | Ollama        |    36    |   17    |    0    |        23.1   |  94.37     |
  | qwen2.5:0.5b-base-q5_1       | 9 HX 375 | Ollama        |    35    |   11    |    0    |        27.5   |  86.98     |
  | qwen2.5:0.5b-base-q5_K_S     | 9 HX 375 | Ollama        |    37    |   10    |    0    |        18.7   |  99.28     |
  | qwen2.5:0.5b-base-q8_0       | 9 HX 375 | Ollama        |    36    |   12    |    0    |        14.7   |  87.27     |
  | qwen2.5:0.5b-instruct-q2_K   | 9 HX 375 | Ollama        |    45    |   11    |    0    |        32.8   | 109.99     |
  | qwen2.5:0.5b-instruct-q3_K_M | 9 HX 375 | Ollama        |    38    |   16    |    0    |        35.6   | 100.94     |
  | qwen2.5:1.5b-instruct-q4_0   | 9 HX 375 | Ollama        |    28    |   11    |    0    |       113.3   |  42.20     |  
  | qwen2.5:1.5b-instruct-q4_1   | 9 HX 375 | Ollama        |    35    |   10    |    0    |       406.3   |  38.55     |
  | qwen2.5:1.5b-instruct-q4_K_M | 9 HX 375 | Ollama        |    36    |    9    |    0    |       276.5   |  44.65     |
  | qwen2.5:1.5b-instruct-q5_0   | 9 HX 375 | Ollama        |    40    |    7    |    0    |       116.2   |  42.13     |
  | qwen2.5:1.5b-instruct-q5_K_M | 9 HX 375 | Ollama        |    37    |    8    |    0    |       311.8   |  42.96     |
  | qwen2.5:1.5b-instruct-q8_0   | 9 HX 375 | Ollama        |    36    |    6    |    0    |       228.7   |  32.71     |
  | qwen2.5:1.5b-instruct-fp16   | 9 HX 375 | Ollama        |    30    |    9    |    0    |       195.0   |  18.68     |
  | qwen2.5:3b-instruct-q3_K_M   | 9 HX 375 | Ollama        |    31    |    8    |    0    |       317.4   |  25.49     |
  | qwen2.5:3b-instruct-q4_0     | 9 HX 375 | Ollama        |    30    |    7    |    0    |       1.0     |  21.38     |
  | qwen2.5:3b-instruct-q4_K_M   | 9 HX 375 | Ollama        |    33    |   11    |    0    |       550.6   |  25.48     |
  | qwen2.5:3b-instruct-q5_0     | 9 HX 375 | Ollama        |    30    |   10    |    0    |       492.8   |  19.35     |
  | qwen2.5:3b-instruct-q5_K_M   | 9 HX 375 | Ollama        |    37    |   11    |    0    |       341.4   |  22.10     |
  | qwen2.5:3b-instruct-q8_0     | 9 HX 375 | Ollama        |    36    |   10    |    0    |       428.6   |  16.71     |
  |  | 9 HX 375 | Ollama        |        |       |    0    |                 |     |
  |  | 9 HX 375 | Ollama        |        |       |    0    |                 |     |
  |  | 9 HX 375 | Ollama        |        |       |    0    |                 |     |
  |  | 9 HX 375 | Ollama        |        |       |    0    |                 |     |
  |  | 9 HX 375 | Ollama        |        |       |    0    |                 |      |
  |  | 9 HX 375 | Ollama        |        |       |    0    |                 |      |
  |  | 9 HX 375 | Ollama        |        |       |    0    |                 |      |

