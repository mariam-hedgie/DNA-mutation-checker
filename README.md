# DNA Mutation Checker 🧬

This is my college Python class project.

This Python project compares DNA sequences from three subjects against a reference DNA sequence. It transcribes the DNA to RNA, translates it into amino acids, checks if the sequences are **synonymous** (same amino acid output despite mutations), and counts the number of mutations needed to make them identical to the reference.

---

## 🧪 Files Included

- `projectB.py`: Main Python script  
- `ref.txt`: Reference DNA sequence  
- `dna1.txt`, `dna2.txt`, `dna3.txt`: Subject DNA sequences to compare  

---

## ▶️ How to Run

### 1. Clone this repository

```bash
git clone https://github.com/mariam-hedgie/DNA-mutation-checker.git
cd DNA-mutation-checker
```

### 2. (Optional) Create and activate a virtual environment

```bash
python3 -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

### 3. Run the script

```bash
python projectB.py
```

Make sure the `.txt` files are in the same folder as `projectB.py`.

---

## 📌 Output Explanation

For each subject DNA file, the script prints:

```
Subject 1 DNA has 3 mutations and is not synonymous
Subject 2 DNA has 2 mutations and is synonymous
Subject 3 DNA has 4 mutation and is not synonymous
```

- `X mutations`: The number of insertions, deletions, or substitutions needed to make the subject DNA match the reference DNA  
- `synonymous`: The resulting amino acid sequence is the same as the reference (mutation does not change the protein)  
- `not synonymous`: The amino acid sequence differs from the reference (mutation changes the protein)  


