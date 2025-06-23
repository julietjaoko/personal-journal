Ultimate Journal Console

A feature-rich command-line journaling application built in Python to help you track your thoughts, moods, and personal growth with style and ease.

✨ Features





Journal Entries: Create regular or gratitude-focused entries with titles, content, mood ratings (1-5), and tags.



Mood Tracking: Visualize mood trends over the last 7 days with an ASCII chart.



Word Frequency Analysis: Discover the most frequently used words in your entries to reflect on recurring themes.



Search Functionality: Search entries by keywords or tags for quick access to past thoughts.



Voice Notes: Record and save voice notes as journal entries (requires sounddevice and numpy).



Goal Setting: Set journaling goals (e.g., 3 entries per week) and track progress with a visual progress bar.



Calendar View: See a monthly calendar highlighting days with entries and view specific day entries.



Export Options: Export your journal in TXT, CSV, or JSON formats for backups or analysis.



Streak Tracking: Monitor your consecutive journaling days to stay motivated.



Colorful Interface: Enhanced with colorama for a vibrant, user-friendly console experience.



Inspirational Quotes: Get a dose of motivation with each session.

📋 Requirements





Python 3.6+



Required packages:





colorama for colored console output



tabulate for beautiful table displays



sounddevice and numpy (optional, for voice note feature)



Install dependencies:

pip install colorama tabulate sounddevice numpy

🚀 Getting Started





Clone or Download: Save the script (journal.py) to your local machine.



Install Dependencies: Run the command above to install required packages.



Run the Application:

python journal.py



Explore the Menu: Use the numbered menu to navigate features like creating entries, viewing mood charts, or exporting your journal.

📖 Usage





Main Menu: Choose from 12 options to create entries, view past entries, set goals, and more.



New Entry: Write a regular entry with a title, content, mood, and tags, or create a gratitude entry listing three things you're thankful for.



Voice Notes: Record audio notes (press Enter to start/stop) and save them as WAV files with a linked journal entry.



Exporting: Save your journal as a TXT, CSV, or JSON file for external use.



Goal Tracking: Set journaling frequency goals (e.g., 3 entries per week) and monitor progress.



Mood Chart: View a 7-day mood trend in an ASCII chart to reflect on your emotional journey.



Calendar View: Display a monthly calendar with marked entry days and dive into specific days' entries.

📂 File Structure





journal.json: Stores journal entries (created automatically).



goals.json: Stores journaling goals (created when setting goals).



voice_notes/: Directory for voice note WAV files (created when recording voice notes).



Exported files: Named with timestamps (e.g., journal_export_20250624_0230.txt).

🛠️ Customization





Modify Quotes: Edit the quotes list in JournalManager.get_inspirational_quote to add your favorite motivational quotes.



Adjust Mood Messages: Update the messages dictionary in JournalManager.get_mood_message for personalized responses.



Extend Export Formats: Add new export formats in JournalManager.export_entries for additional file types.

📝 Example Usage





Create a New Entry:





Select option 1 from the main menu.



Enter a title, write your thoughts, choose a mood (1-5), and add tags.



Receive a mood-specific encouragement message.



View Mood Chart:





Select option 6 to see an ASCII chart of your mood trends over the last 7 days.



Export Journal:





Select option 11, choose a format (TXT, CSV, or JSON), and find the exported file in your directory.

⚠️ Notes





The voice note feature requires a microphone and the sounddevice and numpy packages.



Entries are saved automatically to journal.json after each addition.



Invalid inputs (e.g., non-numeric mood ratings) are handled gracefully with prompts to retry.



The application uses UTF-8 encoding for file operations to support diverse characters.

🌟 Contributing

Feel free to fork this project, submit pull requests, or suggest features via issues. Ideas for enhancements include:





Adding support for multimedia attachments (images, videos).



Implementing sentiment analysis for entries.



Creating a GUI version with Tkinter or PyQt.

📜 License

This project is licensed under the MIT License. Feel free to use, modify, and distribute as you see fit.

🙏 Acknowledgments





Built with Python and powered by colorama and tabulate for a delightful console experience.



Inspired by the joy of journaling and personal growth.

Happy journaling! ✨
