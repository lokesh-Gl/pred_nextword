✍️ Next Word Prediction using LSTM

A simple Streamlit web application that predicts the next word in a sentence using a pre-trained LSTM model. This project demonstrates how sequence models can be used for Natural Language Processing (NLP) tasks such as text prediction.

⸻

🚀 Features (Implemented & Accurate)
	•	⌨️ User input for a sequence of words
	•	🧠 Predicts the next most likely word using an LSTM model
	•	🔁 Uses a saved tokenizer for consistent word indexing
	•	🖥️ Lightweight and easy-to-use Streamlit interface
	•	⚡ Fast inference on CPU

⸻

🧠 Model Details
	•	Model Type: LSTM (Long Short-Term Memory)
	•	Framework: TensorFlow / Keras
	•	Task: Next-word prediction (language modeling)
	•	Model File: next_word_lstm.h5
	•	Tokenizer File: tokenizer.pickle

The model predicts the next word by:
	1.	Tokenizing the input text
	2.	Padding the sequence to the required length
	3.	Feeding it into the LSTM model
	4.	Selecting the word with the highest predicted probability

⸻

🛠️ Tech Stack
	•	Frontend: Streamlit
	•	Deep Learning: TensorFlow (Keras)
	•	NLP Utilities: Keras Tokenizer, Padding
	•	Data Handling: NumPy, Pickle

⸻

⚙️ Installation & Setup

1️⃣ Clone the Repository
``` bash
git clone https://github.com/your-username/next-word-prediction-lstm.git
cd next-word-prediction-lstm
```
2️⃣ Create Virtual Environment (Recommended)
``` bash 
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate    # Windows
```
3️⃣ Install Required Libraries
``` bash
pip install streamlit tensorflow numpy
```
4️⃣ Place Required Files
``` bash
Ensure the following files are present in the project directory:

next_word_lstm.h5
tokenizer.pickle
```
5️⃣ Run the Application
``` bash 
streamlit run app.py
```

⸻

🧪 How the Application Works
	1.	User enters a sequence of words
	2.	Text is converted into token IDs using the tokenizer
	3.	Sequence is padded to match model input length
	4.	LSTM model predicts the probability distribution of the next word
	5.	Word with the highest probability is displayed

⸻

📌 Use Cases
	•	NLP learning and experimentation
	•	Language modeling demonstrations
	•	Text auto-completion prototypes
	•	Academic mini-projects

⸻

🔐 Limitations (Current Implementation)
	•	Predicts only one next word
	•	Accuracy depends heavily on training dataset
	•	No confidence score displayed
	•	No text preprocessing (lowercasing, punctuation removal) in UI

⸻

📈 Future Scope (Not Implemented)
	•	Predict multiple next words
	•	Display top-k predictions with probabilities
	•	Add sentence auto-completion
	•	Improve UI with prediction history

⸻

👨‍💻 Author

Lokesh
Student | AI / ML | Deep Learning

⸻

📜 License

This project is intended for academic and educational purposes.

⸻

Sequence models like LSTM learn context to predict what comes next in language. 🚀
