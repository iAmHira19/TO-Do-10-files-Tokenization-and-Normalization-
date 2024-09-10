# Word Tokenization and Normalization Project

## Overview
This project generates 10 text files, each containing two sentences, and performs word tokenization and normalization. The tokenization splits the text into individual words, and normalization includes converting to lowercase, removing punctuation and stopwords, and lemmatizing the words. The project is implemented in Python and designed to run in Google Colab, where the generated files are zipped and can be downloaded.

## Steps Performed
1. **File Generation:**
   - 10 text files are generated, each containing two sentences.
   - The files are saved in a directory called `generated_files`.

2. **Word Tokenization:**
   - Each file's content is tokenized using the `nltk.tokenize.word_tokenize` function, splitting the text into individual words.

3. **Word Normalization:**
   - Convert words to lowercase.
   - Remove punctuation.
   - Remove common stopwords (e.g., "the", "is").
   - Lemmatize words to reduce them to their base form using `WordNetLemmatizer`.

4. **Download Files:**
   - The generated files are zipped and downloaded as `generated_files.zip`.

## Project Requirements
- **Python 3.x**
- **Libraries:** 
  - `nltk` (Natural Language Toolkit)

### NLTK Data Requirements:
Before running the project, download the necessary NLTK data:
```python
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

## How to Run
1. Clone or download this project.
2. Open it in **Google Colab**.
3. Run the code to:
   - Generate the files.
   - Perform tokenization and normalization.
   - Zip and download the files.

## Output
The code prints the tokenized and normalized words for each file in the console. The generated files are available for download as `generated_files.zip`.

### Example Tokenized and Normalized Output:
For a file containing the sentences:
```text
"This is the first sentence. Here is the second sentence."
```

The output after tokenization and normalization would be:
```python
['first', 'sentence', 'second', 'sentence']
```

## Downloading Files
Once the process is complete, the `generated_files.zip` file containing the 10 text files will be downloaded to your local machine.

## License
This project is licensed under the MIT License.
