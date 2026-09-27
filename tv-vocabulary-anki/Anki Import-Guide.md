## Anki Import Guide

Follow these steps to import the generated vocabulary TSV/Markdown data into your Anki desktop application.

### Prerequisites & Preparation

1. **Copy the Data**: Copy the raw TSV code block containing the vocabulary entries.
2. **Save as UTF-8 Text File**:
   - Open a text editor (e.g., VS Code, Notepad, or Sublime Text).
   - Paste the copied contents into a new file.
   - Save the file as `BCS_S06E08_Anki.tsv` or `BCS_S06E08_Anki.txt`.
   - **Crucial**: Ensure the file encoding is set to **UTF-8** (this guarantees correct rendering of IPA symbols and special characters).

---

### Step-by-Step Import Steps

1. **Open Anki**: Launch your Anki desktop program.
2. **Start Import**:
   - Click **Import File** at the bottom of the main window, or navigate to `File` -> `Import...` (Shortcut: `Ctrl + Shift + I` / `Cmd + Shift + I`).
   - Select your saved `BCS_S06E08_Anki.tsv` file and click **Open**.

3. **Configure Import Options**:
   - **Field Separator**: Select **Tab**.
   - **Allow HTML in fields**: **Check/Enable this box** (essential for rendering the `<b>...</b>` bolding tags in context sentences).
   - **Target Deck**: Select or create your preferred destination deck (e.g., `English::Better Call Saul`).
   - **Note Type**: Choose a note type with at least 8 fields (e.g., `Basic` with extra custom fields, or create a custom `Vocabulary-8-Field` note type).

4. **Map Fields**: Match the 8 TSV columns to your Anki card fields:

   | TSV Column # | Field Name | Description |
   | :---: | :--- | :--- |
   | **1** | Lemma / Expression | Target word or phrase |
   | **2** | IPA | Phonetic pronunciation |
   | **3** | Grammar | Part of speech / Syntactic details |
   | **4** | CEFR Level | Difficulty rating (B2 / C1 / C2) |
   | **5** | Definition (CN) | Chinese definition matching context |
   | **6** | Context Sentence | Original sentence from the TV show |
   | **7** | Daily Sentence | Practical example sentence for daily use |
   | **8** | Status | Verification status (`Normal` / `Pending Verification`) |

5. **Complete Import**: Click **Import** in the top right corner. Anki will confirm the total number of notes successfully added.
