🎵 Malayalam-to-Tamil Songs Lyrics Translation Project



This project translates **Malayalam song lyrics** into **Tamil** (or other languages) and performs **syllable splitting** and **stress analysis** using the `mlphon` phonetic library.

It combines **AI-based translation** (using models like mBART) with detailed **phonetic analysis** to evaluate the quality and rhythm of the translated lyrics.

---

## 🌟 Features

✅ Extract and align song lyric pairs from Malayalam and Tamil  
✅ Perform feature extraction:
- Syllable splitting for Malayalam & Tamil  
- Count total syllables per line  
- Extract rhyme scheme based on last syllables  
- Mark word boundaries  

✅ Train translation model using **mBART** with **K-Fold cross-validation**  
✅ Evaluate translation performance using **BLEU** and **TER** scores  
✅ Provide utility to translate new Malayalam lyric files line by line  
✅ Save translated Tamil lyrics to a new `.txt` file

---

## 🏗 Project Workflow

1️⃣ Upload Malayalam lyrics file  
2️⃣ Translate lyrics using AI model (e.g., mBART)  
3️⃣ Analyze both original and translated lyrics:
- Syllable splitting  
- Stress detection  
4️⃣ Generate evaluation metrics like **BLEU**, **TER** for translation quality  
5️⃣ Export summary as DataFrame or CSV

---

## ⚙️ Installation

1️⃣ Clone or download this repository  

2️⃣ Install required Python packages:
```bash
pip install transformers sentencepiece torch scikit-learn evaluate sacrebleu
```

3️⃣ Place your `songs.zip` in the project folder  
Make sure it contains the following structure:
```
songs.zip/
  songs/
    song1/
      malayalam.txt
      tamil.txt
    song2/
      malayalam.txt
      tamil.txt
```

4️⃣ Run the main script to extract, align, extract features, train, evaluate, and test translations

---

## 📊 Evaluation Metrics

We use:
- **BLEU Score** (Bilingual Evaluation Understudy)  
- **TER Score** (Translation Edit Rate)

to validate translation quality on the aligned dataset.

---

## 📁 Input & Output

- **Input**: Malayalam lyrics (`.txt` files), line by line  
- **Output**: Translated Tamil lyrics saved as `translated_tamil_lyrics2.txt`

---

## 🏆 Authors

This project was done by **Geethu Krishna** and **Malini**  
under the guidance of **Dr Joe Cheri Ross Sir**

---

## 💬 Notes

- Make sure your GPU (if available) is set up to accelerate training.  
- For any issues or improvements, feel free to **fork** this repo and contribute!


"""

