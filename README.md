# 🚀 Smart Financial AI Assistant with PhiData

An intelligent **multi-agent AI assistant** for financial research, capable of providing **real-time stock data, fundamental analysis, analyst recommendations, and financial news**.  

Built with **PhiData Playground**, **Groq models**, and **YFinance tools**, this project demonstrates how AI can automate financial research, provide accurate insights, and support **multi-agent collaboration**.

---

## 📌 Features

- **Multi-Agent System**  
  - **Main Assistant**: Handles general queries and delegates finance-related tasks.  
  - **Financial Agent**: Specialized for financial analysis, stock fundamentals, and analyst recommendations.  

- **AI Models**  
  - Groq Models: `llama-3.1-8b-instant`, `mixtral-8x7b-32768`, `gemma-7b-it`  
  - HuggingFace Models: Integrated for web search and extended queries  
  - Fallback support for robust and reliable responses  

- **Finance Tools**  
  - Real-time stock prices (`get_current_stock_price`)  
  - Stock fundamentals (`get_stock_fundamentals`)  
  - Analyst recommendations (`get_analyst_recommendations`)  
  - Company news  

- **Interactive Playground**  
  - Powered by **PhiData Playground** + **FastAPI**  
  - Supports live queries, multi-agent collaboration, markdown/table outputs  

- **Modular Design**  
  - Financial agent can be imported into other scripts  
  - Agents are reusable and extendable  

---

## 🛠️ Tech Stack

- **Python 3.9+**  
- **PhiData Playground**  
- **Groq API**  
- **HuggingFace API**  
- **YFinance**  
- **FastAPI**  
- **Uvicorn** (for local server)

---

## 📂 Project Structure

<img width="511" height="148" alt="image" src="https://github.com/user-attachments/assets/43f6aa87-436f-494c-8867-fcc16590870a" />


---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/financial-ai-assistant.git
   cd financial-ai-assistant
   ```

2. Create a virtual environment
 ```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
```

3. Install dependencies
```bash
pip install -r requirements.txt

```

4. Set up API keys
```bash
GROQ_API_KEY=your_groq_api_key
HUGGINGFACE_API_KEY=your_huggingface_api_key

```
## ▶️ Usage

1. Run the Playground
```bash
python playground.py

```
Ask queries in the Playground interface
```bash
What is the current stock price of AAPL?

Show me the latest financial fundamentals for Microsoft.

Compare the P/E ratio of AAPL, MSFT, and GOOGL.
```
💬 Example Queries & Outputs
```bash
What is the current stock price of AAPL?

```
Response:
```bash
The current stock price of AAPL is $228.02.

```
Query:
```bash
Show me the latest financial fundamentals for Microsoft.

```
Response (sample):

| Metric         | Value     |
| -------------- | --------- |
| Market Cap     | 3.25T     |
| P/E Ratio      | 35.2      |
| Dividend Yield | 0.82%     |
| EPS            | 9.20      |
| Beta           | 0.89      |
| 52-Week Range  | 280 - 365 |


## 📸 Screenshots / Demo

<img width="1918" height="911" alt="image" src="https://github.com/user-attachments/assets/484913fa-e966-4aa1-9d76-7d61ee20a4ec" />
<img width="1916" height="910" alt="image" src="https://github.com/user-attachments/assets/805a6648-5692-46cb-b79b-891508200ee4" />
<img width="1627" height="612" alt="image" src="https://github.com/user-attachments/assets/fcf63266-eef6-4db3-b2de-73362ba2fb9f" />
<img width="1914" height="1025" alt="2" src="https://github.com/user-attachments/assets/c63dfceb-ad51-425a-bf4c-a5f7c3c01be3" />

🔗 Roadmap
```bash
Add support for balance sheet, income statement, cash flow reports

 Expand to crypto price analysis

 Deploy as a hosted web app with Docker
```
 
 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

📜 License

This project is licensed under the MIT License.

---

Do you also want me to **write the `requirements.txt` file** for this project so that your GitHub repo is **completely runnable** out of the box?


