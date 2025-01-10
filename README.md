# **Small Language Model Chatbot**

## **Project Overview**

The **Small Language Model Chatbot** is a Python-based interactive chatbot built using **Hugging Face's `distilGPT-2`** model. The chatbot is fun, lightweight, and ideal for demonstrating the capabilities of small-scale language models. It includes interactive widgets for user input and a visual element that tracks and displays the word count of user inputs over time.

This project is designed to run seamlessly in **Google Colab**.

---

## **Features**

### 🤖 **Interactive Chatbot**
- Accepts user input and generates meaningful responses using `distilGPT-2`.
- Incorporates randomness and creativity in responses through fine-tuned parameters.

### 📊 **Visualization**
- Displays a bar chart to track the word count of user inputs for each interaction.

### ⚙️ **Enhanced Parameters for Text Generation**
- **`temperature=0.7`**: Balances creativity and determinism.
- **`top_p=0.9`**: Uses nucleus sampling to generate high-quality responses.
- **`min_length=20`**: Ensures meaningful replies.

### 🛡️ **Fallback Mechanism**
- If the chatbot generates a very short or meaningless response, it provides a fallback message:
  ```
  I couldn't think of anything interesting to say! Let's try again.
  ```

---

## **Installation Instructions**

### 1. Clone the Repository
```bash
git clone https://github.com/thekartikeyamishra/small-language-model-chatbot.git
cd small-language-model-chatbot
```

### 2. Install Required Libraries
Make sure to install the necessary Python libraries:
```bash
pip install transformers ipywidgets
```

---

## **How to Use**

1. **Open Google Colab**:
   - Copy and paste the code into a new Google Colab notebook.

2. **Run the Script**:
   - Execute the code cells to initialize the chatbot.

3. **Interact with the Chatbot**:
   - Enter your message in the text input field.
   - Click the **Send** button to receive the chatbot's reply.

4. **View Visualizations**:
   - The chatbot displays a bar chart showing the word count of user inputs after each interaction.

---

#### Visualization:
A bar chart shows the number of words in the user's message for each interaction.

---

## **Potential Enhancements**

1. **Sentiment Analysis**:
   - Add a sentiment analysis layer to analyze the tone of user messages.

2. **Multilingual Support**:
   - Integrate pre-trained multilingual models for global audiences.

3. **Save Conversations**:
   - Allow users to save chat history for later review.

4. **Fine-Tuned Models**:
   - Use domain-specific datasets to fine-tune the chatbot for specific applications (e.g., customer support, education).

5. **Voice Input/Output**:
   - Add support for voice-based interactions using libraries like `SpeechRecognition` and `pyttsx3`.

---

## **Use Cases**

- **Learning Tool**:
  - Explore the capabilities of small language models.
  - Understand text generation and visualization in NLP.

- **Prototyping**:
  - Use this chatbot as a starting point for building advanced conversational AI.

- **Fun and Engagement**:
  - Interact with a lightweight chatbot for entertainment or quick inspiration.

---

## **Contribute**

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## **Support**

If you enjoy using this project, please:
- 🌟 Star this repository on GitHub.
- 🗣️ Share it with your network.
- 💬 Submit feedback or feature requests.

---


## **Acknowledgments**

- **Hugging Face Transformers**: For providing pre-trained models and an intuitive API.
- **Matplotlib**: For data visualization.
- **IPyWidgets**: For building an interactive interface.

---

Let me know if you'd like further refinements or additional sections! 🚀
