# 06_strings_and_casting
# 🧵 06: Strings and Type Casting

### 🧠 Learning Outcomes
* Master string manipulation: Methods (`upper`, `lower`, `replace`) and **f-strings**.
* Understand **Type Casting**: Converting data from one type to another (e.g., `str` to `int`).
* Learn how to handle user inputs safely.

---

### 🤔 Why This Matters for Agentic AI
* **LLMs speak String:** Large Language Models (like GPT-4) receive text (Strings) and output text. You must be an expert at formatting strings to create good prompts.
* **Data Conversion:** LLMs often output numbers as text (e.g., `"The answer is 42"`). You need casting to convert that `"42"` into the number `42` to use it in calculations.

---

### 🔤 String Formatting (F-Strings)
The modern way to combine variables and text.

```python
agent_name = "Jarvis"
task = "Data Analysis"
# The f before the quote allows using {variables} inside
prompt = f"Hello {agent_name}, please start {task}."
