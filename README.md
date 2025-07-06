## 📑 Automation of Document Templating for Academic Administration

This repository contains a **UiPath RPA project** for automating the creation of academic documents (such as certificates, letters, or notices) using dynamic templates and input data.

---

### 📌 Project Purpose

Academic administrators often spend significant time preparing repetitive documents. This automation helps:

* Save time by automatically filling templates
* Reduce human errors
* Standardize output format across departments

---

### 🗂️ Folder Structure

```
/
├── .objects/       # UiPath compiled objects (auto-generated)
├── .project/       # UiPath project files
├── .settings/      # Project settings
├── .tmh/           # Temporary or helper files (if used)
├── Inputs/         # Input files (Excel/CSV data, templates)
├── Main.xaml       # Main workflow file (entry point)
├── project.json    # UiPath project metadata
├── LICENSE         # License information
└── .gitattributes  # Git attributes
```

---

### ⚙️ Requirements

* **UiPath Studio** (recommended: 2021.10 or later)
* **Excel** or **CSV files** as data input (saved in `Inputs/`)
* Microsoft Word installed (if using Word activities)
* Dependencies installed automatically from `project.json`

---

### 🚀 How to Use

1️⃣ **Clone or download** this repository:

```bash
git clone https://github.com/JAYASIMMA/Automation_of_Document_Templating_for_Academic_Administration.git
```

2️⃣ Open `Main.xaml` in **UiPath Studio**.

3️⃣ Verify input files in the `Inputs/` folder.

4️⃣ Click **Run** to execute the workflow.

5️⃣ Generated documents will be saved to the specified output folder (you can configure this in the workflow).

---

### ✅ Workflow Summary

* **Main.xaml:** The main process flow.

  * Reads input data (e.g., student/staff details).
  * Fills predefined Word or PDF templates.
  * Saves completed documents to an output folder.

---

### ✏️ Customization

* Modify templates in `Inputs/` to fit your institution’s style.
* Update the Excel/CSV format to match your data fields.
* Extend the workflow with additional activities (e.g., email the document automatically).

---

### 📜 License

This project is licensed under the [MIT License](LICENSE).

---

### 🙌 Author

**JAYASIMMA**

---
