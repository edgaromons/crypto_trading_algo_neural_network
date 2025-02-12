# crypto_trading_algo_neural_network
In this project, I will show you how to build a Crypto Trading Algorithm Using Neural Network Model.

We:

•	Utilized Python libraries such as Pandas, NumPy, and Matplotlib to develop and implement a cryptocurrency trading algorithm based on Artificial Neural Networks (ANNs).

•	Leveraged TensorFlow/Keras to build, train, and evaluate the ANN for predictive analysis of cryptocurrency price movements.

•	Incorporated technical indicators like Moving Averages (3MA, 10MA, 15MA) to enhance the ANN's predictive capabilities.

•	Utilized financial data APIs (GeckoTerminal DEX API) to extract historical cryptocurrency data for training and backtesting.

•	Applied data preprocessing techniques, including standardization using StandardScaler from Scikit-learn, to prepare data for model training.

•	Evaluated the performance of the ANN model using metrics like accuracy and mean squared error.

•	Visualized the cumulative returns of the trading strategy to assess its profitability.

•	Integrated Alpaca API for potential deployment of the trading strategy in a live trading environment.

Installing Dependencies from requirements.txt
Follow these steps to install the required Python dependencies on your system.
✅ Prerequisites:
•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version
📌 Installation Instructions
🖥️ Windows:
1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🍏 macOS & 🐧 Linux:
1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🔍 Additional Tips:
•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit
# Windows (CMD)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt
•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt
🛠️ Verifying Installation:
Run:
sh
CopyEdit
pip list
to check if all packages are installed.
