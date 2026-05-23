# AI-Based Language Translator

## Introduction
The AI-Based Language Translator is a Python-based project developed to translate text from one language to another using Artificial Intelligence concepts and Google Translator API. This project helps users easily understand and communicate in different languages. It is simple, fast, and beginner-friendly.

This project was created as part of an Artificial Intelligence Internship project to demonstrate the basic implementation of AI-powered language translation.

---

# Objectives
- To develop a simple AI-based translator tool
- To understand the use of APIs in Python
- To improve programming and problem-solving skills
- To provide quick and accurate language translation

---

# Features
- Translate text instantly
- Supports multiple languages
- Easy command-line interface
- Fast and accurate translation
- Beginner-friendly Python project

---

# Technologies Used
- Python
- Google Colab
- deep-translator Library
- Artificial Intelligence Concepts

---

# Libraries Used
```python
from deep_translator import GoogleTranslator
```

---

# Installation
Run the following command in Google Colab or Python environment:

```python
!pip install deep-translator
```

---

# Project Working
1. User enters text
2. User selects a language
3. The translator processes the text
4. AI-based translation is generated
5. Output is displayed on the screen

---

# Supported Languages
| Language | Code |
|----------|------|
| Hindi | hi |
| French | fr |
| Spanish | es |

---

# Source Code

```python
!pip install deep-translator

from deep_translator import GoogleTranslator

print("================================")
print("   AI-Based Language Translator")
print("================================")

while True:

    text = input("\nEnter text to translate: ")

    print("\nChoose language:")
    print("1. Hindi")
    print("2. French")
    print("3. Spanish")

    choice = input("Enter choice (1/2/3): ")

    if choice == "1":
        lang = "hi"
    elif choice == "2":
        lang = "fr"
    elif choice == "3":
        lang = "es"
    else:
        print("Invalid choice!")
        continue

    translated = GoogleTranslator(source='auto', target=lang).translate(text)

    print("\nTranslated Text:")
    print(translated)

    again = input("\nDo you want to translate again? (yes/no): ")

    if again.lower() != "yes":
        print("\nThank you for using AI Translator App!")
        break
```

---

# Sample Output

```python
================================
   AI-Based Language Translator
================================

Enter text to translate: Hello

Choose language:
1. Hindi
2. French
3. Spanish

Enter choice (1/2/3): 1

Translated Text:
नमस्ते
```

---

# Advantages
- Saves time in communication
- Easy to use
- Helps users learn new languages
- Useful for students and beginners

---

# Future Enhancements
- Add more languages
- Add speech-to-text feature
- Create graphical user interface (GUI)
- Add voice translation support
- Improve translation accuracy

---

# Conclusion
The AI-Based Language Translator is a simple and effective project that demonstrates the implementation of Artificial Intelligence in language translation. It provides fast and accurate results and helps users communicate in different languages easily.

---

# Author
Kadambini Behera

Artificial Intelligence Intern
