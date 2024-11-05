# Real-Time AI Stock Advisor with Ollama (Llama 3) &amp; Streamlit

This project uses LLM-powered insights to fetch stock data every minute, analyze trends, and provide real-time, easy-to-understand explanations.

[InsiderFinance](https://wire.insiderfinance.io/real-time-ai-stock-advisor-with-ollama-streamlit-c8ce727c236f)


## Local Development Setup

  - Create a Python virtual environment and activate
	
	```shell
	python -m venv dev
	```
	
	```powershell
	.\dev\Scripts\activate
	```
	
	```shell
	dev/Scripts/activate
	```

  - Install the packages and dependencies as listed in requirements file
	
	```shell
	pip install -r requirements.txt --no-cache-dir --disable-pip-version-check
	```

  - Run the Streamlit app
  
    ```shell
	streamlit run stock_advisor.py
	```