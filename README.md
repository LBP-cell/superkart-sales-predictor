# SuperKart Sales Forecasting System 🛒

An end-to-end Machine Learning web application that predicts product sales performance across SuperKart retail outlets using an optimized, tuned **XGBoost Regressor** pipeline.

## 🏗️ Architecture
The system is built using a decentralized microservices design:
* **Backend:** A Flask API endpoint (`port:7860`) that deserializes your trained model pipeline to handle single and batch predictions.
* **Frontend:** An interactive Streamlit interface (`port:8501`) allowing operational teams to compute store sales in real time.
* **Orchestration:** Managed smoothly inside Docker containers via `docker-compose`.

## 🚀 How to Run (GitHub Codespaces)
1. Open this repository inside your **GitHub Codespace**.
2. Open your terminal window and start the application container mesh by running:
   ```bash
   docker compose up --build
   ```
3. Once compiled, follow the local dashboard links generated in your browser to test your predictions!
