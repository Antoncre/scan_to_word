The application serves as Images to word converter. It is usefull specifically when we have scanned documents and we need a text representation of them

1. Go to your desired location on your PC and clone this repository: ```git clone https://github.com/Antoncre/scan_to_word```
2. Download Tesseract: https://github.com/UB-Mannheim/tesseract/wiki
3. Install choosing all additional languages needed (this application uses specifically Polish language)
4. Create virtual environment: ```python -m venv venv```
5. activate virtual environment on Windows: ```venv\Scripts\activate.bat```, on Linux: ```source venv/bin/activate```
6. install dependecies ```pip install pillow pytesseract python-docx```
7. Run the app ```python main.py```
