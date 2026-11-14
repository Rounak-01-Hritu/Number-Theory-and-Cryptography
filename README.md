#Name: Most. Rounak Binta Ali Hirtu
#ID: IT23037


# Number-Theory-and-Cryptography
# 🔐 Number Theory and Cryptography Workshop

## 📌 About the Workshop

This repository contains the learning materials, lecture slides, assignments, practical exercises, and cryptography demonstrations from the **Number Theory and Cryptography Workshop**, organized by the **Maths and Physics Club, IIT Bombay**.

The workshop introduces fundamental mathematical concepts behind number theory and explores their applications in modern cryptography. It combines theoretical learning through lecture slides and assignments with practical implementation using Python and Jupyter Notebooks.

The repository is organized into two major sections:

1. **Number Theory** – Fundamental mathematical concepts, lecture slides, and problem-solving assignments.
2. **Cryptography** – Practical cryptographic algorithms, demonstrations, RSA challenges, and hands-on exercises.

This repository serves as a record of my learning and practical work throughout the workshop.

---

## 🎯 Workshop Objectives

The main objectives of this workshop are:

- Understand the fundamentals of number theory.
- Learn about prime numbers, divisibility, and primality testing.
- Understand modular arithmetic and its applications.
- Implement important mathematical algorithms using Python.
- Explore public-key cryptography and the RSA cryptosystem.
- Understand encryption, decryption, and cryptographic attacks.
- Practice solving real-world cryptographic problems.
- Develop problem-solving skills through mathematical and programming exercises.

---

## 📂 Repository Structure

The repository is divided into two main directories.

```text
Number_Theory_and_Cryptography_Workshop/
│
├── Number Theory/
│   │
│   ├── Slides/
│   │   ├── Day 0.pdf
│   │   ├── Day 1.pdf
│   │   └── Day 2.pdf
│   │
│   ├── Assignments/
│   │   ├── Day 1 Assignment.ipynb
│   │   └── Day 2 Assignment.pdf
│   │
│   └── README.md
│
├── Cryptography/
│   │
│   ├── Demo Session.ipynb
│   ├── Many-Time Pad.ipynb
│   ├── RSA Assignment.ipynb
│   ├── RSA Quest.ipynb
│   ├── RSA Quiz.ipynb
│   ├── Handout for Cryptography.pdf
│   │
│   └── References/
│       └── Additional reference materials
│
└── README.md
```

*Note: The structure above describes the main workshop resources. Individual filenames and additional reference files may vary in the downloaded repository.*

---

# 📘 Part 1: Number Theory

Number Theory is the branch of mathematics that studies integers and their properties. It provides the mathematical foundation for many cryptographic systems.

This section contains lecture slides and assignments covering the fundamental concepts of number theory.

## 1. Lecture Slides

The Number Theory section includes three lecture slide PDFs.

| File | Description |
|---|---|
| Day 0.pdf | Introductory workshop materials |
| Day 1.pdf | Number theory concepts and mathematical foundations |
| Day 2.pdf | Further number theory concepts and applications |

These materials provide the theoretical background needed to understand the mathematical problems and algorithms used in the assignments.

## 2. Day 1 Assignment

**File:** `Day 1 Assignment.ipynb`

The first assignment focuses on implementing fundamental number theory algorithms using Python.

The major topics include:

- Extended Euclidean Algorithm
- Greatest Common Divisor (GCD)
- Least Common Multiple (LCM)
- Linear Diophantine Equations
- Modular Inverse
- Modular Division
- Fast Modular Exponentiation
- Chinese Remainder Theorem

### Learning Outcomes

Through this assignment, I practiced implementing mathematical algorithms, solving modular arithmetic problems, and understanding how number theory operations are used in cryptography.

## 3. Day 2 Assignment

**File:** `Day 2 Assignment.pdf`

The second assignment explores additional number theory problems and mathematical proofs.

The assignment includes:

- Repunit sequences and divisibility properties
- Perfect numbers and their mathematical characterization
- Fermat pseudoprimes
- Properties of prime numbers and modular arithmetic

### Learning Outcomes

This assignment helped develop mathematical reasoning and proof-writing skills while exploring deeper relationships between integers, prime numbers, and divisibility.

---

# 🔐 Part 2: Cryptography

Cryptography is the practice of securing information through mathematical techniques. It plays an important role in protecting digital communication, authentication, and data confidentiality.

The Cryptography section contains lecture resources, practical demonstrations, programming assignments, and cryptographic challenges.

## 1. Cryptography Handout

**File:** `Handout for Cryptography.pdf`

The handout provides supporting theoretical material for understanding cryptographic systems and the concepts demonstrated throughout the practical sessions.

It serves as a reference while working through the cryptography notebooks and assignments.

## 2. Demo Session

**File:** `Demo Session.ipynb`

This notebook demonstrates important cryptographic concepts through practical Python implementations.

The demonstration covers:

- **Diffie–Hellman Key Exchange:** Understanding how two parties can establish a shared secret over an insecure communication channel.
- **RSA Cryptosystem:** Exploring public-key encryption and decryption.
- **Shor's Algorithm:** Demonstrating the relationship between quantum computing and integer factorization.
- **Cyclic Groups:** Exploring mathematical structures used in cryptographic systems.

### Learning Outcomes

This session provided practical exposure to public-key cryptography, key exchange, mathematical groups, and the relationship between number theory and cryptographic security.

## 3. Many-Time Pad

**File:** `Many-Time Pad.ipynb`

This practical exercise demonstrates a major security weakness that occurs when a one-time pad key is reused for multiple messages.

Topics covered:

- One-Time Pad encryption
- ASCII and hexadecimal conversion
- XOR operations
- Encryption and decryption
- Reusing the same key for multiple messages
- Recovering information through ciphertext analysis
- Guessing common plaintext patterns

### Important Concept

A one-time pad is secure only when its key is:

1. Truly random.
2. Kept secret.
3. At least as long as the message.
4. Used only once.

Reusing the same key can expose relationships between plaintext messages and make cryptanalysis possible.

## 4. RSA Assignment

**File:** `RSA Assignment.ipynb`

This assignment focuses on implementing the RSA cryptosystem and exploring different attacks against vulnerable RSA configurations.

The assignment covers seven major problems:

| Question | Topic |
|---|---|
| Q1 | RSA Encryption |
| Q2 | RSA Decryption |
| Q3 | Simple Ciphertext Attack |
| Q4 | Factoring RSA with a Small Prime |
| Q5 | Factoring RSA with Small Prime Difference |
| Q6 | Common Divisor Attack |
| Q7 | Hastad's Broadcast Attack |

### Key Concepts

- Public and private keys
- RSA encryption and decryption
- Prime factorization
- Modular inverses
- Fermat factorization
- Greatest Common Divisor
- Chinese Remainder Theorem
- RSA cryptanalysis

### Learning Outcomes

Through this assignment, I gained practical experience implementing RSA operations and understanding how weaknesses in key generation or RSA usage can make encrypted messages vulnerable to different attacks.

## 5. RSA Quest

**File:** `RSA Quest.ipynb`

The RSA Quest is a puzzle-based cryptography challenge that combines several algorithms and techniques from the previous assignments.

Instead of solving isolated mathematical problems, the quest involves recovering encrypted messages and combining them to discover secret links that lead to subsequent challenges.

The quest incorporates:

- RSA Decryption
- RSA Encryption
- Simple Message Deciphering
- Small Prime Factorization
- Small Prime Difference Factorization
- Common Divisor Attack
- Hastad's Broadcast Attack

### Quest Progression

The challenge follows a sequence of stages:

1. Solve the initial RSA decryption puzzle.
2. Recover another secret message using RSA encryption and simple deciphering.
3. Combine the recovered strings to construct the first secret link.
4. Solve additional RSA challenges using the information from the secret document.
5. Construct the next secret link.
6. Solve the remaining RSA attacks.
7. Combine the recovered messages to obtain the final answer.

### Learning Outcomes

The quest helped reinforce the practical applications of RSA algorithms and demonstrated how multiple mathematical techniques can be combined to solve cryptographic challenges.

---

# 🧠 Key Concepts Learned

Throughout the workshop, I explored the following mathematical and cryptographic concepts.

| Category | Concepts |
|---|---|
| Number Theory | Divisibility, prime numbers, perfect numbers, repunits |
| Algorithms | Euclidean Algorithm, Extended Euclidean Algorithm |
| Modular Arithmetic | Modular inverse, modular division, modular exponentiation |
| Mathematical Theorems | Chinese Remainder Theorem, Fermat's Little Theorem |
| Primality | Primality testing, Fermat pseudoprimes |
| Cryptography | One-Time Pad, RSA, Diffie–Hellman |
| Cryptographic Attacks | Small-prime factorization, Fermat factorization, Common Divisor Attack, Hastad's Broadcast Attack |
| Programming | Python functions, Jupyter Notebooks, algorithm implementation |

---

# 🛠️ Tools and Technologies

The following tools and technologies were used throughout the workshop:

| Tool / Technology | Purpose |
|---|---|
| Python | Implementing mathematical and cryptographic algorithms |
| Jupyter Notebook | Writing and executing practical exercises |
| Google Colab | Running notebooks in a cloud environment |
| Git and GitHub | Managing and organizing workshop materials |
| PDF Documents | Studying lecture slides, assignments, and reference materials |

---

# 🚀 How to Use This Repository

### 1. Clone the Repository

Open a terminal and execute:

```bash
git clone https://github.com/mnp-club/Number_Theory_and_Cryptography_Workshop.git
```

### 2. Enter the Project Directory

```bash
cd Number_Theory_and_Cryptography_Workshop
```

### 3. Explore the Learning Materials

- Open the PDFs inside `Number Theory/Slides/` to study the lecture materials.
- Open the assignments inside `Number Theory/Assignments/`.
- Read the cryptography handout.
- Explore the practical notebooks inside the `Cryptography/` directory.

### 4. Run the Jupyter Notebooks

You can run the notebooks using either Jupyter Notebook or Google Colab.

**Using Google Colab:**

1. Visit [Google Colab](https://colab.research.google.com/).
2. Select **File → Upload notebook**.
3. Upload the desired `.ipynb` file.
4. Execute the notebook using **Runtime → Run all**.
5. Follow the instructions and examine the outputs.

---

# 🎓 Overall Learning Outcomes

Completing the workshop materials and assignments provided practical experience in both number theory and cryptography.

The major learning outcomes include:

- Understanding fundamental number theory concepts and mathematical proofs.
- Implementing important mathematical algorithms using Python.
- Applying modular arithmetic to solve computational problems.
- Understanding the mathematical foundation of RSA encryption.
- Implementing encryption and decryption operations.
- Exploring cryptographic vulnerabilities through practical attacks.
- Understanding the importance of secure key generation and key management.
- Analyzing ciphertexts and recovering plaintext messages.
- Connecting theoretical mathematical concepts with practical cryptographic applications.

---

# 🙏 Acknowledgement

I would like to express my gratitude to the **Maths and Physics Club, IIT Bombay**, for organizing the Number Theory and Cryptography Workshop and providing the learning resources, lecture materials, assignments, and practical cryptographic challenges.

The workshop provided an opportunity to explore the mathematical foundations of cryptography through both theoretical study and hands-on programming exercises.

---

## 📌 References

- [Original Workshop Repository – Maths and Physics Club, IIT Bombay](https://github.com/mnp-club/Number_Theory_and_Cryptography_Workshop)
- [Google Colab](https://colab.research.google.com/)
- Workshop lecture slides, assignments, handouts, and reference materials included in this repository.

---

**Workshop:** Number Theory and Cryptography Workshop  
**Organized by:** Maths and Physics Club, IIT Bombay  
**Main Topics:** Number Theory, Modular Arithmetic, and Cryptography  
**Programming Language:** Python  
**Platform:** Jupyter Notebook / Google Colab  
**Status:** Completed ✅
