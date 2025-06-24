# Ultimate Journal Console

A feature-rich command-line journaling application built in Python to help you track your thoughts, moods, and personal growth with style and ease.

## ✨ Features

- **Journal Entries**: Create regular or gratitude-focused entries with titles, content, mood ratings (1-5), and tags.
- **Mood Tracking**: Visualize mood trends over the last 7 days with an ASCII chart.
- **Word Frequency Analysis**: Discover the most frequently used words in your entries to reflect on recurring themes.
- **Search Functionality**: Search entries by keywords or tags for quick access to past thoughts.
- **Voice Notes**: Record and save voice notes as journal entries (requires `sounddevice` and `numpy`).
- **Goal Setting**: Set journaling goals (e.g., 3 entries per week) and track progress with a visual progress bar.
- **Calendar View**: See a monthly calendar highlighting days with entries and view specific day entries.
- **Export Options**: Export your journal in TXT, CSV, or JSON formats for backups or analysis.
- **Streak Tracking**: Monitor your consecutive journaling days to stay motivated.
- **Colorful Interface**: Enhanced with `colorama` for a vibrant, user-friendly console experience.
- **Inspirational Quotes**: Get a dose of motivation with each session.

## 📋 Requirements

- Python 3.6+
- Required packages:
  - `colorama` for colored console output
  - `tabulate` for beautiful table displays
  - `sounddevice` and `numpy` (optional, for voice note feature)
- Install dependencies:
  ```bash
  pip install colorama tabulate sounddevice numpy
  ```

## 🚀 Installation
Clone the repository:

```bash
git clone https://github.com/yourusername/ultimate-journal-console.git
```
Navigate to the project directory:

```bash
cd ultimate-journal-console
```
Install dependencies:

```bash
pip install -r requirements.txt
```

## 📖 Usage
**Run the application:**

```bash
python journal_app.py
```
**Main Menu Options:**
- Create new journal entry

- Create gratitude entry

- View all entries

- Search entries

- Record voice note

- View mood chart

- Set journaling goals

- View goal progress

- View calendar

- View word frequency

- Export journal

- Exit

## 📂 File Structure
```text
.
├── journal.json            # Stores journal entries
├── goals.json              # Stores journaling goals
├── voice_notes/            # Directory for voice note WAV files
├── exports/                # Directory for exported files
└── journal_app.py          # Main application file
```
## 🛠️ Customization
**Edit these files to personalize your experience:**

- Modify quotes in JournalManager.get_inspirational_quote

- Update mood messages in JournalManager.get_mood_message

- Add new export formats in JournalManager.export_entries

## 🌟 Contributing
**Contributions are welcome! Ideas for enhancements:**

- Multimedia attachments support

- Sentiment analysis for entries

- GUI version with Tkinter/PyQt

## 📜 License
MIT License

## 🙏 Acknowledgments
- Python community for the versatile programming language

- Colorama & Tabulate developers for enhanced console experience

- All contributors and users who make this tool meaningful

**Happy journaling! ✨**
