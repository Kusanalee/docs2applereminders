**README.md**

**Google Docs to Apple Reminders**

This Python script imports data from a table in a Google Doc to the Apple Reminders app. It can be used to migrate existing reminders from Google Docs to Apple Reminders, or to keep the two apps in sync.

**Requirements:**

* Python 3
* Google Docs API
* Apple Reminders API

**Instructions:**

1. Install the required Python packages:

```python
pip install google-api-python-client oauth2client pygmo
```

2. Create a new Google Docs API project and obtain an OAuth 2.0 client ID and secret.

3. Create a new Apple Reminders API project and obtain an App Specific Password.

4. Update the `config.py` file with your Google Docs API project credentials and Apple Reminders API project App Specific Password.

5. Run the script:

```python
python main.py
```

The script will prompt you to select the Google Doc containing the table of reminders to import. Once you have selected the Google Doc, the script will import the reminders to the Apple Reminders app.

**Example table of reminders:**

| Title | Due Date | Priority |
|---|---|---|
| Buy groceries | 2023-09-25 | High |
| Go to the dentist | 2023-10-01 | Medium |
| Pay rent | 2023-10-05 | Low |

**Usage:**

To import the reminders in the example table above, run the script and select the Google Doc containing the table. The script will import the reminders to the Apple Reminders app as follows:

* Reminder: Buy groceries
    * Due date: 2023-09-25
    * Priority: High

* Reminder: Go to the dentist
    * Due date: 2023-10-01
    * Priority: Medium

* Reminder: Pay rent
    * Due date: 2023-10-05
    * Priority: Low

**Troubleshooting:**

If you are having trouble importing reminders, check the following:

* Make sure that you have installed the required Python packages.
* Make sure that you have updated the `config.py` file with your Google Docs API project credentials and Apple Reminders API project App Specific Password.
* Make sure that you have selected the correct Google Doc containing the table of reminders to import.

If you are still having trouble, please open an issue on the project repository.
