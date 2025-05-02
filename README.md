🎵 Song Translation
This project translates Malayalam song lyrics into other languages (like Tamil) and performs syllable splitting and stress analysis using the mlphon phonetic library.

It combines AI-based translation (e.g., using mBART or similar models) with detailed phonetic analysis to help evaluate the quality and rhythm of translated lyrics.

🌟 Features
✅ Translate Malayalam song lyrics to another language (e.g., Tamil)
✅ Extract syllables from original and translated lyrics
✅ Identify stressed vs. unstressed syllables (based on long vowel markers)
✅ Compare rhythm and stress patterns between original and translated versions
✅ Output detailed analysis in tabular (DataFrame) format

🏗 Project Workflow
1️⃣ Upload Malayalam lyrics file 
2️⃣ Translate lyrics using AI model (e.g., mBART)
3️⃣ Analyze both original and translated lyrics:

Syllable splitting

Stress detection
4️⃣ Generate evaluation metrics like BLEU, TER for translation quality
5️⃣ Export summary as DataFrame or CSV
