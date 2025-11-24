🌍 English to Indian Languages Translator
A simple, interactive command-line translator that converts text between English and 10 major Indian languages using the Google Translate API.
Features
•	Bi-directional Translation: Translate from English to Indian languages and vice versa
•	10 Indian Languages Supported: 
o	Hindi (हिंदी)
o	Bengali (বাংলা)
o	Tamil (தமிழ்)
o	Telugu (తెలుగు)
o	Marathi (मराठी)
o	Gujarati (ગુજરાતી)
o	Kannada (ಕನ್ನಡ)
o	Malayalam (മലയാളം)
o	Punjabi (ਪੰਜਾਬੀ)
o	Urdu (اردو)

•	User-Friendly Interface: Simple menu-driven interface
•	Free to Use: Uses the free Google Translate API
Prerequisites
•	Python 3.6 or higher
•	Internet connection (required for translation API)

Installation
Step 1: Clone or Download the Project
git clone <your-repository-url>
cd translator-project
Or simply download the translator.py file to your computer.

Step 2: Install Required Libraries
Open your terminal/command prompt and run:
pip install googletrans==3.1.0a0

Important: Make sure to install version 3.1.0a0 specifically, as newer versions may have compatibility issues.
Usage
Running the Translator
1.	Open your terminal/command prompt
2.	Navigate to the folder containing translator.py
3.	Run the program: translator.py

How to Use
Select a Language: Choose from the menu (1-10) to select your target Indian language
Choose Direction: 
Option 1: English → Indian Language
Option 2: Indian Language → English
Enter Text: Type or paste the text you want to translate
View Results: The translation will be displayed instantly
Continue or Exit: Press Enter to translate more text or type 'exit' to quit

Example Usage
     ENGLISH ↔ INDIAN LANGUAGES TRANSLATOR
Select target language:
1. Hindi
2. Bengali
3. Tamil
...
Enter your choice (0-10): 1

✓ Selected Language: Hindi

Translation Direction:
1. English → Hindi
2. Hindi → English

Choose direction (1 or 2): 1

Enter text to translate (or 'back' to return): Hello, how are you?

Translating...

Original (English): Hello, how are you?
Translated (Hindi): नमस्ते, आप कैसे हैं?

Troubleshooting
RuntimeWarning: coroutine 'Translator.translate' was never awaited
If you see this error, it means you have a newer version of googletrans installed. Fix it by:
pip uninstall googletrans
pip install googletrans==3.1.0a0

AttributeError or Translation Errors
•	Check your internet connection
•	Verify you have the correct version installed: pip show googletrans
•	Try reinstalling: pip uninstall googletrans && pip install googletrans==3.1.0a0

Module Not Found Error
Make sure you've installed the library:
pip install googletrans==3.1.0a0

Tips
•	For best results, use proper grammar and punctuation
•	The translator works best with complete sentences rather than single words
•	You can translate paragraphs of text, not just single sentences
•	Type 'back' to return to the language selection menu
•	Type 'exit' when prompted to quit the program
•	Press Ctrl+C at any time to force quit

 Limitations
•	Requires active internet connection
•	Translation accuracy depends on Google Translate API
•	May have rate limits on the free API
•	Complex or technical terms may not translate perfectly
•	Idiomatic expressions may be translated literally

Contributing
Feel free to fork this project and submit pull requests for:
•	Adding more languages
•	Improving the user interface
•	Adding new features (translation history, favorites, etc.)
•	Bug fixes

License
This project is open source and available for educational purposes.

Support
If you encounter any issues or have questions:
1.	Check the Troubleshooting section above
2.	Ensure you have the correct version of googletrans installed
3.	Verify your internet connection is stable

Enjoy translating!



