# LLM RAG Demo
- Install Python 3.10 (Anaconda based installation is preferred)
- Create a virtual environment
  - `conda create -n "env name here" python=3.10`
- Activate the environment
  - `conda activate "env name here"`

- Install the dependencies
  - `pip install -r req.txt`

- Create OpenAI and Google API Keys
  - [OpenAI](https://platform.openai.com/api-keys)
  - [Google](https://aistudio.google.com/app/apikey)

- Create a file named `.env` in this folder and store keys in the format shown in `.env_syntax` (This step is necessaary as the file `.env` will be referred in the code notebook.)

After above steps are followed successfully, you will be able to run the notebooks `RAG_Demo_OpenAI.ipynb` and `gemini-rag.ipynb` without any errors.

Actual content files (pdf, txt and jpg) in this repo are used as demo, you can test these APIs on your own files as well.