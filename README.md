# 🧪 TDD & BDD Practice Project

This project is a hands-on practice repository for exploring **Test-Driven Development (TDD)** and **Behavior-Driven Development (BDD)** concepts using Python, `unittest`, and `behave`.

It is based on coursework from IBM's *Introduction to BDD* course on Coursera and has been extended and modified for personal exploration and deeper understanding.

---

## What’s Included

- 13 Testing lab
- `features/` – BDD scenarios using `behave`, including:
  - `.feature` files for behavior specifications
  - Step definitions for linking behavior to Python code
- Example workflows for:
  - Test-Driven Development (TDD)
  - Behavior-Driven Development (BDD)

---

## Getting Started

1. **Clone the repo**

```bash
git clone https://github.com/dahomyarii/tdd-bdd-practice.git
cd tdd-bdd-practice
```

2. **Set up a virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is not provided, manually install:
> ```bash
> pip install behave
> ```

4. **Run Unit Tests**

```bash
python -m unittest test_calculator.py
```

5. **Run BDD Tests**

```bash
behave
```

---

## Learning Goals

This project helped reinforce:

- Writing unit tests before code (TDD)
- Using BDD with Gherkin syntax (`Given`, `When`, `Then`)
- Understanding the role of test automation in agile workflows
- Practicing clean, testable Python code

---

## Modifications by Me

This project was originally provided by [IBM Developer Skills Network](https://github.com/ibm-developer-skills-network/duwjx-tdd_bdd_PracticeCode/)  
Modifications and enhancements were made by **[@dahomyarii](https://github.com/dahomyarii)** in 2025.

---


## License

This project is based on code licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

- See the [`LICENSE`](LICENSE) file for full license terms.
- See the [`NOTICE`](NOTICE) file for attribution details.

---

## Credits

This project is based on the work and course materials provided by
[IBM Developer Skills Network](https://github.com/ibm-developer-skills-network)

Connect with him on LinkedIn: [John Rofrano](https://www.linkedin.com/in/JohnRofrano/)
