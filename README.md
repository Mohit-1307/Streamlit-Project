# Streamlit Examples Collection

This repository is a **learning-oriented collection of Streamlit scripts** demonstrating core to advanced Streamlit concepts. Each file focuses on a specific feature such as widgets, forms, layouts, session state, caching, reruns, multipage apps, and data visualization.

The goal is to help you **understand Streamlit’s execution model and UI patterns through small, focused examples**.

---

## 📁 Project Structure Overview

```
.
├── text_elements.py
├── data_elements.py
├── chart_elements.py
├── form_elements.py
├── simple_form.py
├── advanced_form.py
│
├── session_state1.py
├── session_state2.py
├── session_state3.py
├── callbacks.py
├── rerun.py
│
├── caching1.py
├── caching2.py
│
├── layouts.py
├── fragments.py
├── streamlit_dataflow.py
│
├── multi_pages_app.py
│
├── advance_widget_concepts1.py
├── advance_widget_concepts2.py
│
├── .gitignore
└── README.md
```

---

## 🧱 Basic UI & Text Elements

### `text_elements.py`

Demonstrates basic text and display elements:

* `st.title`, `st.header`, `st.subheader`
* Markdown rendering
* Code blocks
* Divider and captions
* Image rendering

Use this file to learn **how Streamlit renders text and static content**.

---

## 📊 Data & Visualization

### `data_elements.py`

Covers data display features:

* `st.dataframe` (interactive)
* `st.data_editor`
* `st.table` (static)
* Metrics (`st.metric`)
* JSON and dictionary rendering

### `chart_elements.py`

Shows multiple charting options:

* Line, bar, area charts
* Scatter plots
* Map visualization
* Matplotlib integration (`st.pyplot`)

Useful for understanding **Streamlit’s native vs external plotting support**.

---

## 📝 Forms & User Input

### `simple_form.py`

A basic form example:

* Text inputs
* Date & time inputs
* Radio, selectbox, sliders
* Submit handling

### `advanced_form.py`

More realistic form handling:

* Validation logic
* Multiple input types
* Conditional feedback
* Balloons 🎈 on success

### `form_elements.py`

Demonstrates:

* Grouping widgets inside `st.form`
* Separating form submission from UI logic

These files explain **why forms behave differently from normal widgets**.

---

## 🔄 Session State (Very Important)

### `session_state1.py`

Shows what happens **without session state** (counter resets on every run).

### `session_state2.py` & `session_state3.py`

Demonstrate:

* Persistent counters
* Reset functionality
* Correct usage of `st.session_state`

These files are critical to understanding **Streamlit’s rerun-based execution model**.

---

## 🔁 Callbacks & Reruns

### `callbacks.py`

Illustrates widget callbacks using `on_change` and session state.

### `rerun.py`

Demonstrates:

* `st.rerun()`
* Immediate UI updates
* Controlled reruns after state changes

Essential for **advanced interactivity**.

---

## ⚡ Caching & Performance

### `caching1.py`

Uses `@st.cache_data`:

* Caching slow computations
* Time-based cache invalidation (TTL)

### `caching2.py`

Uses `@st.cache_resource`:

* Persisting resources like file handles
* Managing lifecycle-sensitive objects

Helps you learn **when to cache data vs resources**.

---

## 🧩 Layouts & UI Structure

### `layouts.py`

Covers layout primitives:

* Sidebar
* Tabs
* Columns
* Containers
* Expanders
* Placeholders (`st.empty`)

### `fragments.py`

Demonstrates `@st.fragment()`:

* Isolated UI updates
* Partial rerendering
* Modular UI blocks

Useful for **performance and clean UI separation**.

---

## 🔀 Streamlit Execution Model

### `streamlit_dataflow.py`

Demonstrates:

* Script top-to-bottom execution
* Button behavior
* Rerun mechanics

Helps explain **why buttons feel “stateless”** without session state.

---

## 📑 Multipage Applications

### `multi_pages_app.py`

Implements a manual multipage app using:

* Sidebar navigation
* Function-based pages
* Charts, maps, and dataframes per page

Useful for building **larger Streamlit applications**.

---

## 🎛 Advanced Widget Concepts

### `advance_widget_concepts1.py`

Covers:

* Dependent sliders
* Dynamic default values
* Session-controlled widgets

### `advance_widget_concepts2.py`

Covers:

* Conditional rendering
* Widget toggling
* Preserving user input

These examples highlight **non-obvious widget behavior**.

---

## 🔧 Miscellaneous

### `.gitignore`

Configured to ignore:

* Python cache files
* Virtual environments
* IDE configs
* ML artifacts
* Secrets and environment files

---

## ▶️ How to Run Any Example

```bash
pip install streamlit
streamlit run filename.py
```

Example:

```bash
streamlit run session_state2.py
```

---

## 🎯 Learning Recommendations

Suggested learning order:

1. `text_elements.py`
2. `data_elements.py`, `chart_elements.py`
3. `simple_form.py` → `advanced_form.py`
4. `session_state1.py` → `session_state3.py`
5. `callbacks.py`, `rerun.py`
6. `caching1.py`, `caching2.py`
7. `layouts.py`, `fragments.py`
8. `multi_pages_app.py`

---

## ✅ Who This Is For

* Beginners learning Streamlit
* Developers confused about reruns & session state
* Anyone building interactive data apps

---

If you want, I can:

* Convert this into **GitHub-ready README.md**
* Add **architecture diagrams**
* Refactor files into a **course-style structure**
* Explain **Streamlit internals** step-by-step

---

## ▶️ How to Run
git clone https://github.com/Mohit-1307/Streamlit-Project.git

---

## ⭐ Support

If this repository helps you:

⭐ Star the repo

🔁 Share with learners
