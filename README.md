## Setup Guide: Ollama with DeepSeek-R1

### 1. Install Ollama

* Go to [ollama.com](https://ollama.com/), install it.
* Download model [deepseek-r1](https://ollama.com/library/deepseek-r1)
  * `ollama run deepseek-r1:7b`

### 2. UI Integration Using OpenWebUI


* Easy Docker Way  [github.com/open-webui](https://github.com/open-webui/open-webui?tab=readme-ov-file#installation-with-default-configuration)

### 2.1 Open WebUI with Search Engine Access
* Admin Panel -> Settings -> Websearch
* Google_PSE
  * create a google [PSE Account](https://programmablesearchengine.google.com/)
  * toggle "Search across the web"
  * you may also want to select a region for better search results
  * get api key
  * copy api key and engine Id into Web Search Settings

### 2.2 Integration with IDE (Jetbrains)

* go to settings -> plugins
* search in marketplace for codeGPT
* go to settings -> tools -> codeGPT -> providers -> ollama
* refresh models
* select model
* check code completion


### 3. Ollama API
   https://github.com/ollama/ollama/blob/main/docs/api.md
   https://www.postman.com/postman-student-programs/ollama-api/documentation/suc47x8/ollama-rest-api

