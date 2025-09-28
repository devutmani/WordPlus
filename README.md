# WordPlus

Word Frequency Counter is a simple yet powerful application designed to analyze text documents or user inputs by counting the frequency of each unique word. The tool displays words and their corresponding frequencies in descending order, making it easy to identify the most common terms in any given text.

---

## 📑 Table of Contents

- [✨ Features](#features)
- [🛠️ How It Works](#how-it-works)
- [📊 Graphical Representation & Visualization](#graphical-representation--visualization)
- [📝 Example](#example)
- [🚀 Usage](#usage)
- [⚙️ Implementation Details](#implementation-details)
- [🌐 Supported Languages](#supported-languages)
- [🤝 Contributing](#contributing)
- [📄 License](#license)

---

## ✨ Features

- **Input Support:** Read text from documents or direct user input.
- **Efficient Counting:** Uses a dictionary data structure for fast lookups and updates.
- **Sorted Output:** Displays word-frequency pairs in descending order of frequency.
- **Case Handling:** Optionally handles case sensitivity (e.g., treats "Word" and "word" as the same or different).
- **Punctuation Management:** Strips punctuation to ensure accurate word counts.
- **Graphical Visualization:** View word frequency data as bar charts or pie charts for easy analysis.
- **Interactive Visuals:** Explore word frequency visually with interactive plots (e.g., zoom, hover, filter).

---

## 🛠️ How It Works

1. **Text Reading:** The application reads the entire text from a file or input.
2. **Word Extraction:** The text is split into words, removing punctuation and normalizing case as needed.
3. **Frequency Counting:** Each word is stored in a dictionary, where words are keys and frequencies are values.
4. **Sorting:** The dictionary is sorted in descending order based on word frequency.
5. **Display:** The sorted list and graphical visualizations of word frequencies are displayed to the user.

---

## 📊 Graphical Representation & Visualization

Word Frequency Counter supports graphical visualization to help users understand word distributions at a glance:

- **Bar Chart:** Shows the frequency of the top N words for quick comparison.
- **Pie Chart:** Visualizes the proportion of word usage in the text.
- **Interactive Plots:** (If applicable) Use libraries like Matplotlib, Seaborn, or Plotly to allow users to interact with the plots—hover to see details, zoom in/out, or filter words.

### Example Bar Chart

![Example Bar Chart](assets/bar_chart_example.png)

### Example Pie Chart

![Example Pie Chart](assets/pie_chart_example.png)

*Sample images above are for illustration. Actual charts generated will reflect your input text.*

---

## 📝 Example

Suppose you input the following text:
```
Hello world! Hello everyone. Welcome to the world of coding.
```
The output will be:
```
hello: 2
world: 2
everyone: 1
welcome: 1
to: 1
the: 1
of: 1
coding: 1
```
**Graphical Output:**  
A bar chart will show "hello" and "world" as the tallest bars, with other words as shorter bars.  
A pie chart will display each word as a slice, sized according to frequency.

---

## 🚀 Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/devutmani/WordPlus.git
   cd WordPlus
   ```

2. Run the application according to the instructions in your preferred language (see below).

3. (Optional) To enable graphical visualization, ensure you have the required plotting libraries installed (e.g., `matplotlib`, `plotly`, or `seaborn` for Python).

---

## ⚙️ Implementation Details

This project leverages the dictionary (hash map) data structure to store word-frequency pairs efficiently:
- **Dictionary Keys:** Unique words from the text.
- **Dictionary Values:** The number of times each word appears.

This approach ensures fast insertion and retrieval, even for large texts.

---

## 🌐 Supported Languages

> The implementation may vary depending on your preferred programming language. Please see the source files in the repository for language-specific instructions.

---

## 🤝 Contributing

Contributions and suggestions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

MIT License

Copyright (c) 2023 Dev Kumar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

**Author:** [Dev Kumar](https://github.com/devutmani)
