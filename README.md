## <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/streamlit/streamlit-original.svg" height="26"/> Streamlit Playbook

A Hands-on Guide to Mastering Streamlit’s Execution Model & UI Patterns
A learning-first collection of focused Streamlit examples, designed to build deep intuition about how Streamlit works under the hood — from basic UI elements to advanced concepts like session state, reruns, caching, fragments, and multipage apps.

📌 Learn Streamlit by observing how small scripts behave, not by copying large apps.

---

## 🚀 Why This Repository?

✔️ Structured like a mini Streamlit course

✔️ Focuses on Streamlit’s execution & rerun model

✔️ Small, isolated examples (easy to reason about)

✔️ Covers both beginner → advanced concepts

✔️ Ideal for debugging “why did my app rerun?” moments

This repository exists to answer questions like:

* Why does my variable reset?

* Why does a button feel stateless?

* When should I use session_state vs caching?

* How do forms and callbacks really work?

---

## 🎯 Who Is This For?

This repository is ideal for:

✔️ 🧑‍💻 Beginners learning Streamlit

✔️ 📊 Data Scientists building interactive apps

✔️ 🤯 Developers confused about reruns & session state

✔️ 🚀 Engineers moving from notebooks → apps

If you’ve ever said “Streamlit is simple, but confusing” — this is for you.

---

## 📚 Learning Outcomes

* After completing this repository, you will:

* Understand Streamlit’s top-to-bottom execution model

* Use session state correctly and confidently

* Build forms, callbacks, and controlled reruns

* Optimize apps using data & resource caching

* Design clean layouts and modular UIs

* Create multipage Streamlit applications

* Avoid common beginner mistakes

---

## 📚 Prerequisites

* Basic Python programming (variables, functions, conditionals)

* Familiarity with running Python scripts (command line or terminal basics)

* Basic understanding of data structures (lists, dictionaries, DataFrames – helpful but not mandatory)

* No prior Streamlit experience required (this repository starts from fundamentals)

✅ Optional (Nice to Have)

* Basic knowledge of Pandas or NumPy

* Experience with Jupyter Notebooks

* Interest in building interactive data apps

---

## 🗺️ Learning Path

### 🧭 Visual Roadmap (Streamlit Fundamentals → Production-Ready Apps)

📌 Follow this path sequentially to build deep intuition about Streamlit’s execution model, UI behavior, and performance patterns — not just surface-level syntax.

```
FOUNDATION — HOW STREAMLIT THINKS
│
├── Streamlit Execution Basics
│   ├── Top-to-Bottom Script Execution
│   ├── What Causes a Rerun?
│   ├── Why Variables Reset
│   └── Why Buttons Feel Stateless
│
│   📁 Files:
│   ├── streamlit_dataflow.py
│   └── text_elements.py
│
BASIC UI & CONTENT RENDERING
│
├── Text & Static Elements
│   ├── Titles, Headers, Markdown
│   ├── Code Blocks & Captions
│   ├── Images & Dividers
│   └── Understanding UI as Script Output
│
│   📁 Files:
│   └── text_elements.py
│
DATA DISPLAY & VISUALIZATION
│
├── Data Rendering
│   ├── st.dataframe vs st.table
│   ├── st.data_editor
│   ├── Metrics & JSON Display
│   └── When UI Triggers Reruns
│
├── Charts & Plots
│   ├── Native Streamlit Charts
│   ├── Line, Bar, Area, Scatter
│   ├── Maps
│   └── Matplotlib Integration (st.pyplot)
│
│   📁 Files:
│   ├── data_elements.py
│   └── chart_elements.py
│
USER INPUT & FORMS
│
├── Basic Widgets
│   ├── Text Inputs, Sliders, Selectboxes
│   ├── Radios, Dates, Times
│   └── Widget Default Behavior
│
├── Forms (Critical Concept)
│   ├── st.form() Execution Model
│   ├── Why Forms Don’t Rerun Immediately
│   ├── Submit Button Semantics
│   └── Validation & Feedback Patterns
│
│   📁 Files:
│   ├── simple_form.py
│   ├── advance_form.py
│   └── form_elements.py
│
SESSION STATE — CORE STREAMLIT SKILL
│
├── Stateless vs Stateful Apps
│   ├── Variable Reset Problem
│   ├── Session Initialization Patterns
│   └── Persistent UI Behavior
│
├── Practical Session State
│   ├── Counters & Toggles
│   ├── Reset Logic
│   ├── Controlled State Mutation
│   └── Avoiding Common Pitfalls
│
│   📁 Files:
│   ├── session_state1.py
│   ├── session_state2.py
│   └── session_state3.py
│
CALLBACKS & RERUN CONTROL
│
├── Widget Callbacks
│   ├── on_change Mechanics
│   ├── Session-Driven Updates
│   └── Predictable UI Reactions
│
├── Explicit Reruns
│   ├── st.rerun()
│   ├── Immediate UI Refresh
│   └── Controlled Execution Flow
│
│   📁 Files:
│   ├── callbacks.py
│   └── rerun.py
│
CACHING & PERFORMANCE
│
├── Data Caching
│   ├── @st.cache_data
│   ├── Cache Invalidation
│   ├── TTL-Based Refresh
│   └── Preventing Unnecessary Recomputations
│
├── Resource Caching
│   ├── @st.cache_resource
│   ├── Models & DB Connections
│   └── Lifecycle-Aware Persistence
│
│   📁 Files:
│   ├── caching1.py
│   └── caching2.py
│
LAYOUTS & UI ARCHITECTURE
│
├── Layout Primitives
│   ├── Sidebar, Columns, Tabs
│   ├── Containers & Expanders
│   ├── Placeholders (st.empty)
│   └── Responsive UI Design
│
├── Fragments (Advanced)
│   ├── @st.fragment()
│   ├── Partial UI Rerendering
│   ├── Modular UI Blocks
│   └── Performance-Friendly Updates
│
│   📁 Files:
│   ├── layouts.py
│   └── fragments.py
│
MULTIPAGE APPLICATIONS
│
├── Manual Multipage Architecture
│   ├── Sidebar Navigation
│   ├── Function-Based Pages
│   ├── Page-Specific State & Data
│   └── Scaling App Structure
│
│   📁 Files:
│   └── multi_pages_app.py
│
ADVANCED WIDGET PATTERNS
│
├── Dynamic & Dependent Widgets
│   ├── Conditional Rendering
│   ├── Dynamic Defaults
│   ├── Widget Toggling
│   └── Preserving User Input Across Reruns
│
│   📁 Files:
│   ├── advance_widget_concepts1.py
│   └── advance_widget_concepts2.py
│
PRODUCTION READINESS
│
├── Mental Models You’ll Master
│   ├── Rerun-First Thinking
│   ├── State vs Cache Decisions
│   ├── Predictable UI Behavior
│   └── Debugging “Why Did This Rerun?”
│
└── Next Steps
    ├── Build Full Dashboards
    ├── Connect APIs & Databases
    ├── Deploy on Streamlit Cloud
    └── Scale to Production Apps
    |
```

---

## 🧩 Project Structure

### 🧱 1️⃣ Basic UI & Text Elements

#### text_elements.py

* Learn how Streamlit renders static content:

* Titles, headers, subheaders

* Markdown & code blocks

* Captions & dividers

* Image rendering

📌 Goal: Understand how Streamlit builds UI from Python scripts

### 📊 2️⃣ Data Display & Visualization

#### data_elements.py

* Covers data rendering options:

* st.dataframe (interactive)

* st.data_editor

* st.table (static)

* Metrics (st.metric)

* JSON & dictionary display

#### chart_elements.py

* Visualization examples using:

* Line, bar, area charts

* Scatter plots

* Maps

* Matplotlib (st.pyplot)

📌 Goal: Learn native vs external plotting behavior

### 📝 3️⃣ Forms & User Input

#### simple_form.py

* Introduces basic forms:

* Text, date, time inputs

* Selectboxes, radios, sliders

* Submit button handling

#### advance_form.py

* Realistic form patterns:

* Validation logic

* onditional feedback

* Success indicators

#### form_elements.py

Explains:

* st.form() behavior

* Why forms don’t rerun on every widget change

📌 Goal: Understand why forms behave differently

### 🔄 4️⃣ Session State (Critical Concept)

#### session_state1.py

* Shows what happens without session state

➡️ Variables reset on every rerun.

* session_state2.py & session_state3.py

* Demonstrates:

* Persistent counters

* Reset logic

* Correct state initialization patterns

📌 Goal: Master Streamlit’s rerun-based execution model

### 🔁 5️⃣ Callbacks & Reruns

#### callbacks.py

* Widget callbacks (on_change)

* Session-driven updates

#### rerun.py

* st.rerun()

* Controlled reruns

* Immediate UI refresh patterns

📌 Goal: Build responsive, interactive apps

### ⚡ 6️⃣ Caching & Performance

#### caching1.py – @st.cache_data

* Cache slow computations

* TTL-based invalidation

#### caching2.py – @st.cache_resource

* Persist resources (models, DB connections)

* Lifecycle-aware caching

📌 Goal: Learn what to cache and why

### 🧩 7️⃣ Layouts & UI Structure

#### layouts.py

* Sidebar

* Tabs

* Columns

* Containers

* Expanders

* Placeholders (st.empty)

#### fragments.py

* Uses @st.fragment():

* Partial rerendering

* Modular UI blocks

* Performance-friendly updates

📌 Goal: Design clean, scalable layouts

### 🔀 8️⃣ Streamlit Execution Model

#### streamlit_dataflow.py

Demonstrates:

* Top-to-bottom script execution

* Button behavior

* Rerun mechanics

📌 Explains why buttons feel “stateless”

### 📑 9️⃣ Multipage Applications

#### multi_pages_app.py

* Manual multipage app using:

* Sidebar navigation

* Function-based pages

* Page-specific data & charts

📌 Foundation for larger Streamlit apps

### 🎛 🔟 Advanced Widget Concepts

#### advance_widget_concepts1.py

* Dependent widgets

* Dynamic defaults

* Session-controlled widgets

#### advance_widget_concepts2.py

* Conditional rendering

* Widget toggling

* Preserving user input

📌 Covers non-obvious widget behavior

---

⚙️ .gitignore

Ignore rules for Python, Jupyter, virtual environments, and system files.

---

## 🛠️ Tech Stack & Tools

* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="26"/> Python

* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/streamlit/streamlit-original.svg" height="26"/> Streamlit

* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="26"/> Numpy – Numerical computation

* <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="26"/> Pandas – Data manipulation

* <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" height="26"/> Matplotlib – Statistical data visualization

---

## ▶️ How to Run Locally

* Follow these steps to set up and run the Streamlit Playbook repository on your local machine

### 1️⃣ Clone the Repository

git clone https://github.com/Streamlit-Playbook.git

cd Streamlit-Playbook

### 2️⃣ (Optional but Recommended) Create a Virtual Environment

#### 🪟 Windows:

python -m venv venv

venv\Scripts\activate

#### <img src="https://upload.wikimedia.org/wikipedia/commons/3/30/MacOS_logo.svg" height="28"/> macOS / 🐧 Linux:

python3 -m venv venv

source venv/bin/activate

### 3️⃣ Install Dependencies

* Upgrade pip and install all required libraries.

pip install --upgrade pip

pip install -r requirements.txt

* If requirements.txt is not present, install manually

pip install streamlit numpy pandas matplotlib

### 4️⃣ Run Streamlit Examples

* Each concept in this repository is a standalone Streamlit script.

#### Run any file using:

streamlit run filename.py

#### Examples:

streamlit run text_elements.py

📌 Open the browser URL shown in the terminal (usually http://localhost:8501).

---

## 📘 Documentation

📄 README.md

* Explains the purpose and vision of the repository

* Describes the complete folder and noteboook structure

* Guides learners on how to follow the learning path step-by-step

* Provides setup instructions and usage guidelines

* Acts as a quick reference for learners, contributors, and recruiters

---

## 🌟 Support & Contribution

If this repository helps you:

⭐ Star the repository 🔁 Share it with fellow learners

Contributions are welcome! Feel free to open issues or submit pull requests.

---

📌 Author
Mohit Singh Rajput

Machine Learning & Data Science Enthusiast
