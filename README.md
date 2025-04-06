# Smart Audio Text Accuracy 🎙️📝

This project focuses on building an automated pipeline to convert audio files into text using Speech Recognition and evaluate the accuracy of the transcriptions. Additionally, it checks the grammatical correctness of the converted text to provide deeper insights into speech quality and clarity.

---

## Features 🚀

- Convert audio (.wav / .mp3) files to text using Google Speech Recognition API.
- Handle unrecognized speech and errors gracefully.
- Evaluate transcription accuracy against ground-truth text.
- Grammar and spelling check using `language_tool_python`.
- Generate detailed reports in CSV format.
- Ready to integrate with real-world audio datasets.

---

## Tech Stack 🛠️

- Python
- SpeechRecognition
- LanguageTool
- Pandas
- Difflib (for accuracy comparison)
