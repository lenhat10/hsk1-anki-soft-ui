# 🌟 HSK1 Anki Template - Soft UI Edition

Welcome to the **HSK1 Anki Template**! This Note Type is specially designed for Anki to make learning HSK1 Chinese vocabulary more visual, engaging, and less tedious with a modern Soft UI design.

## ✨ Key Features

* 🎨 **Elegant Soft UI:** Harmonious colors, soft rounded corners, and an incredibly compact display on both desktop and mobile (minimizing the need to scroll).
* 🕹️ **Integrated MCQ:** Practice with multiple-choice questions right on the Anki card, complete with a countdown timer for an added challenge.
* ⌨️ **Typing Practice:** Includes an input box to practice typing Pinyin or Hanzi, with automatic correct/incorrect validation.
* 🪄 **Smart Interaction:** The "English Example" button is collapsed by default and only expands when clicked, keeping the screen clutter-free.
* 🔊 **Audio & Pronunciation:** Scientifically arranged audio buttons (Pinyin, Meaning, Example Sentence) for easy interaction.

## 📸 Screenshots
Card 1: Multiple Choices - Front & Back template

<img width="516" height="584" alt="image" src="https://github.com/user-attachments/assets/029eabc2-0f4e-45bd-b28a-1a67ff0ca505" /> 
*Front interface featuring the multiple-choice question.*

<img width="516" height="584" alt="image" src="https://github.com/user-attachments/assets/dbf9efe5-7f21-4c8f-a4c8-f79adc2e095b" /> 
*Back interface with detailed meanings and expanded examples.*

Card 2: Typing Cards - Front & Back template

<img width="516" height="584" alt="image" src="https://github.com/user-attachments/assets/f1b6709a-1032-48a6-a6fe-5bae729b4faa" />
<img width="516" height="584" alt="image" src="https://github.com/user-attachments/assets/a96134e7-ec71-453e-b151-f01f3ac6868d" />

Card 3: Hanzi Writing - Front & Back template

<img width="516" height="584" alt="image" src="https://github.com/user-attachments/assets/ac3e91d9-20f3-46f3-9f33-5cad5a160bfe" />
<img width="516" height="584" alt="image" src="https://github.com/user-attachments/assets/d9de298c-a58c-4d4f-b03b-8e2037cf9646" />

## 🚀 Installation Guide

To use this template, follow these steps within the Anki app:

1. Open Anki, go to **Tools** > **Manage Note Types**.
2. Click **Add** > **Clone: Basic** and name it `HSK1_Template 3 CARDS`.
3. Select your newly created Note Type and click **Cards...**.
4. In the styling window:
   * Copy the content of the `Front.html` file from this repository and paste it into the **Front Template** box.
   * Copy the content of the `Back.html` file and paste it into the **Back Template** box.
   * Copy the content of the `Style.css` file and paste it into the **Styling** box.
5. Click **Save** and you're all set!

> **Note:** Make sure you have created all the corresponding Fields (e.g., Hanzi, Pinyin, Meaning, Audio, etc.) in the **Fields...** menu of your Note Type to match the HTML code.

## 📝 Guide to Importing Data from Excel (.xlsx / .csv)

To bulk-add vocabulary to this template, you can use Anki's Import feature.

**Step 1: Prepare your data file**
* Open your Excel file and ensure the data columns are arranged to match the Fields in the Note Type (e.g., Column A is Hanzi, Column B is Pinyin, Column C is Meaning...).
* **Important Tip:** To avoid parsing errors, it is highly recommended to `Save As` your Excel file as **CSV UTF-8 (Comma delimited) (*.csv)** or **Text (Tab delimited) (*.txt)**.

**Step 2: Import into Anki**
1. Open Anki and click on **File** > **Import...**.
2. Select the `.xlsx`, `.csv`, or `.txt` file you just saved.
3. A configuration window will appear. Pay special attention to the following settings:
   * **Type:** You must select the exact Note Type you created for this template (e.g., `HSK1 Soft UI`).
   * **Deck:** Choose the deck where you want to save your new cards.
   * **Field mapping:** Carefully verify that the columns from your file match the corresponding fields in Anki (e.g., ensure `Field 1` maps correctly to `Column 1`).

**⚠️ Common Issue: Column Mismatch Error**
If you encounter an error message like: `Exception: Found 19 fields but 18 field types`, it means your import file contains more columns than the number of fields configured in your Anki Note Type. 
* **How to fix:** Highlight and completely delete any seemingly empty columns at the far right of your Excel file. Alternatively, if you are using a standard CSV, check if any of your text cells contain stray commas (`,`), which might cause Anki to mistakenly split that text into a new column.
* 
## 🤝 Contributing
This project was created to share with and help the Chinese learning community. If you have ideas to improve the interface or optimize the code, feel free to open a Pull Request or submit an Issue!

---
*Happy studying! 💮*
