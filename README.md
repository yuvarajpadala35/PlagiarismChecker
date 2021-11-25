# Plagiarism-checker-Python

This repo consists of a source code of a python script to detect plagiarism in textual document using **cosine similarity**



## How is it done?

You might be wondering on how plagiarism detection on textual data is done, well it aint that complicated as you may think.

We all all know that computer are good at numbers, so in order to compute the simlilarity between on two text documents, the textual  raw data is transformed into vectors => arrays of numbers and then from that we are going to use a basic knowledge vector to compute the the similarity between them.

This repo consist of a basic example on how to do that.


Before you begin playing with the source code you might need to install deps just as shown below;

```bash
pip3 install -r requirements.txt
```

## Running the App

To run this code you need to have your textual document in your project directory with extension **.txt** and then when you run the script, it will automatically loads all the document with that extension and then compute the similarity between them just as shown below;

```bash
$-> cd Plagiarism-checker-Python
$ Plagiarism-checker-Python-> python3 app.py
('john.txt', 'juma.txt', 0.5465972177348937)
('fatma.txt', 'john.txt', 0.14806887549598566)
('fatma.txt', 'juma.txt', 0.18643448370323362)

```

