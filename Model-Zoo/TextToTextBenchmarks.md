## MediaTek Genio Series
  
  | Model            |  Chipsets  |    Framework          |    Speed (token/s)<br><sub>Prompt/Eval |   Memory (GB) |  Power (Watt) |     Temp (°C)    |
  |------------------|------------|-----------------------|--------------------|---------------|---------------|------------------|
  | deepseek-r1:1.5b |  Genio-510 | Ollama(`Cortex-A78`)   |   9.76/ 5.86      | 4GB (100%)    |               |                  |
  | llama3.2:1b      |  Genio-510 | Ollama(`Cortex-A78`)   |   21.06/ 6.44     | 4GB (100%)    |               |                  |

## AMD Ryzen AI 300 Series



  | Model                        |  Chipsets  |  Framework  |  CPU (%) | GPU (%) | NPU (%) | Memory (GB) |  Time-to-first-Token (ms) |  Speed (token/s)  |
  |------------------------------|------------|-------------|----------|---------|---------|-------------|---------------------------|-------------------|
  | qwen2.5:latest               | 9 HX 375 | Ollama(`VGM`) |    34    |    4    |    0    |             |       676.5217ms          |  11.26 tokens/s   |
  | qwen2.5:0.5b-base-q2_K       | 9 HX 375 | Ollama(`VGM`) |    33    |   10    |    0    |             |        17.6474ms          | 108.76 tokens/s   |
  | qwen2.5:0.5b-base-q3_K_S     | 9 HX 375 | Ollama(`VGM`) |    37    |   12    |    0    |             |        21.0013ms          | 104.98 tokens/s   |
  | qwen2.5:0.5b-base-q3_K_M     | 9 HX 375 | Ollama(`VGM`) |    45    |   11    |    0    |             |         20.664ms          | 102.63 tokens/s   |  
  | qwen2.5:0.5b-base-q3_K_L     | 9 HX 375 | Ollama(`VGM`) |    38    |   12    |    0    |             |        20.5134ms          | 105.15 tokens/s   |
  | qwen2.5:0.5b-base-q4_0       | 9 HX 375 | Ollama(`VGM`) |    32    |   15    |    0    |             |        21.6852ms          |  99.54 tokens/s   |
  | qwen2.5:0.5b-base-q4_1       | 9 HX 375 | Ollama(`VGM`) |    33    |   10    |    0    |             |        26.0319ms          |  99.45 tokens/s   |
  | qwen2.5:0.5b-base-q4_K_S     | 9 HX 375 | Ollama(`VGM`) |    30    |    7    |    0    |             |         18.859ms          | 112.33 tokens/s   |
  | qwen2.5:0.5b-base-q4_K_M     | 9 HX 375 | Ollama(`VGM`) |    38    |   13    |    0    |             |        19.0301ms          |  96.10 tokens/s   |
  | qwen2.5:0.5b-base-q5_0       | 9 HX 375 | Ollama(`VGM`) |    36    |   17    |    0    |             |        23.1507ms          |  94.37 tokens/s   |
  | qwen2.5:0.5b-base-q5_1       | 9 HX 375 | Ollama(`VGM`) |    35    |   11    |    0    |             |        27.5554ms          |  86.98 tokens/s   |
  | qwen2.5:0.5b-base-q5_K_S     | 9 HX 375 | Ollama(`VGM`) |    37    |   10    |    0    |             |        18.7671ms          |  99.28 tokens/s   |
  | qwen2.5:0.5b-base-q8_0       | 9 HX 375 | Ollama(`VGM`) |    36    |   12    |    0    |             |        14.7824ms          |  87.27 tokens/s   |
  | qwen2.5:0.5b-instruct-q2_K   | 9 HX 375 | Ollama(`VGM`) |    45    |   11    |    0    |             |        32.8394ms          | 109.99 tokens/s   |
  | qwen2.5:0.5b-instruct-q3_K_M | 9 HX 375 | Ollama(`VGM`) |    38    |   16    |    0    |             |        35.6802ms          | 100.94 tokens/s   |
  | qwen2.5:1.5b-instruct-q4_0   | 9 HX 375 | Ollama(`VGM`) |    28    |   11    |    0    |             |       113.3365ms          |  42.20 tokens/s   |  
  | qwen2.5:1.5b-instruct-q4_1   | 9 HX 375 | Ollama(`VGM`) |    35    |   10    |    0    |             |       406.3834ms          |  38.55 tokens/s   |
  | qwen2.5:1.5b-instruct-q4_K_M | 9 HX 375 | Ollama(`VGM`) |    36    |    9    |    0    |             |       276.5872ms          |  44.65 tokens/s   |
  | qwen2.5:1.5b-instruct-q5_0   | 9 HX 375 | Ollama(`VGM`) |    40    |    7    |    0    |             |       116.2599ms          |  42.13 tokens/s   |
  | qwen2.5:1.5b-instruct-q5_K_M | 9 HX 375 | Ollama(`VGM`) |    37    |    8    |    0    |             |       311.8687ms          |  42.96 tokens/s   |
  | qwen2.5:1.5b-instruct-q8_0   | 9 HX 375 | Ollama(`VGM`) |    36    |    6    |    0    |             |       228.7796ms          |  32.71 tokens/s   |
  | qwen2.5:1.5b-instruct-fp16   | 9 HX 375 | Ollama(`VGM`) |    30    |    9    |    0    |             |       195.0062ms          |  18.68 tokens/s   |
  | qwen2.5:3b-instruct-q3_K_M   | 9 HX 375 | Ollama(`VGM`) |    31    |    8    |    0    |             |       317.4983ms          |  25.49 tokens/s   |
  | qwen2.5:3b-instruct-q4_0     | 9 HX 375 | Ollama(`VGM`) |    30    |    7    |    0    |             |       1.0217379s          |  21.38 tokens/s   |
  | qwen2.5:3b-instruct-q4_K_M   | 9 HX 375 | Ollama(`VGM`) |    33    |   11    |    0    |             |       550.6926ms          |  25.48 tokens/s   |
  | qwen2.5:3b-instruct-q5_0     | 9 HX 375 | Ollama(`VGM`) |    30    |   10    |    0    |             |       492.8077ms          |  19.35 tokens/s   |
  | qwen2.5:3b-instruct-q5_K_M   | 9 HX 375 | Ollama(`VGM`) |    37    |   11    |    0    |             |       341.4379ms          |  22.10 tokens/s   |
  |  | 9 HX 375 | Ollama(`VGM`) |        |       |    0    |             |                 |     |
  |  | 9 HX 375 | Ollama(`VGM`) |        |       |    0    |             |                 |     |
  |  | 9 HX 375 | Ollama(`VGM`) |        |       |    0    |             |                 |     |
  |  | 9 HX 375 | Ollama(`VGM`) |        |       |    0    |             |                 |     |
  |  | 9 HX 375 | Ollama(`VGM`) |        |       |    0    |             |                 |     |
  |  | 9 HX 375 | Ollama(`VGM`) |        |       |    0    |             |                 |      |
  |  | 9 HX 375 | Ollama(`VGM`) |        |       |    0    |             |                 |      |
  |  | 9 HX 375 | Ollama(`VGM`) |        |       |    0    |             |                 |      |

