# 🌟 Literature Poem Generator (using Neural Networks)👾 📝
This project is a poem generator using Sequential Neural Network. It learns from existing poems and generates new ones based on the patterns it discovers.

## Let’s dive into the details 🚀⭐ :

## ⭐How It Works ⭐
 ### 1) Data Preparation: 
 - The collection of poems stored in a file called “poem.txt.”
+ We read each line of the poems and create a list to store them.
### 2) Tokenization:
 - Create a Tokenizer to learn the words in the poems.
* The tokenizer assigns a unique number to each word (like giving each word a secret code).
      
### 3) Creating N-Grams:
* Then ,  slide a window over the words to create a small group of words (called an “n-gram”).
* These n-grams help our model understand the structure and flow of the poems.
### 4) Building the Model:
* This model consist of three layers .
* **Embedding Layer**: Converts word indices to dense vectors (like translating words into a secret language).
* **Bidirectional LSTM Layer** : This layer remembers patterns in the poems (like remembering a song’s melody both forwards and backwards).
* **Dense Layer** : Predicts the next word in the poem (like guessing the next word in a sentence).
### 5)Training the Model:
Then we can train our model using the input sequences (the n-grams) and their corresponding labels (the next words).
After several rounds of practice (epochs of 40), our model gets better at creating new poems.

## Usages ⭐
How this Model helps : 
- Content Creation 📝 : Blogs and Websites , Social Media
- Personalized Marketing 📝: Marketers can send personalized poems to subscribers during special occasions or holidays.
- Creative Writing 📝: Students can use this tool to explore language nuances and improve their writing skills.
---
## Installation ⚙️

TO SET UP PROJECT 🚀: 
```bash
# Example installation steps
git clone [https://github.com/yourusername/your-repo.git](https://github.com/Madhusri02/Poem-Generator.git)
pip install numpy tensorflow streamlit
```
tu run the file : 
```python

streamlit run streamlit_app.py
```

## ⭐⭐ IMAGES ⭐⭐

 ### Output generated📚 : 
   ![Image of the screenshot](https://github.com/Madhusri02/Poem-Generator/blob/main/Screenshot%202024-03-15%20064200.png)



