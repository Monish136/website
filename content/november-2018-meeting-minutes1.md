Title: Meeting Minutes - Chennaipy Nov 2018 Meetup
Date: 2018-11-22
Tags: Meeting Minutes
Summary: This document contains the meeting minutes from the **Chennaipy Nov 2018 Meetup**.

# Meeting Minutes - Chennaipy Nov 2018 Meetup

Hi Sharmila, thanks for the detailed take on the event!

Regards,  
Vijay Kumar

---

## Introduction to PyGTK
### Speaker: Ashok Kumar

The author used PyGTK in their Digital Signage Project to manage many LCD and LED devices. They need to display images, videos, and webpages.

They used **Xibo**, an open-source software to manage remote displays and schedule content. Each player was a remote node.

### PyGTK
- Built on the GTK+ library, PyGTK exposes most of the features available in GTK+.
- Works on **Windows**, **MacOS**, **Linux**.
- Several advantages over GTK+:
  - No need to worry about pointers and memory management.
  - Quick prototyping and easy development.
- **Widgets**: Components for building interfaces.
  - Control and display widgets.
  - Containers for holding widgets (e.g., Window, frames).

### Glade
- GUI creation using drag-and-drop.
- The exported XML can be used directly in PyGTK to build the program, saving hours of coding.

## Accessing Spreadsheets in Python
### Speaker: Praveen Kumar

Praveen emphasized using **virtualenv** to clone the Python environment and avoid conflicts with the system Python.

### Steps to Access Spreadsheets Programmatically:
- Connect to the workbook.
- Access the worksheet and read/write cells.
- Modify and save cells.

### Spreadsheet from Scratch in Python
- Automates manual tasks.
- Uses **MS Excel** or **LibreOffice** spreadsheets.
- Data stored in text files (e.g., **Yaml** for version control).

---

## Lightning Talks

### Spicing up the Command Line
#### Speaker: Aziz

Aziz demonstrated how to enhance the command line using Python libraries:
- **getpass**: Prompt the user for a password without echoing.
- **colorama**: Simple cross-platform API for printing colored terminal text.
- **tabulate**: Pretty-print tabular data.
- **tqdm**: Show a smart progress meter.
- **jinja**: HTML formatted output.

### Contributing to Open Source Projects
#### Speaker: Karthick

Karthick encouraged contribution to **Python** projects, especially for bug triaging, documentation, and community building. He emphasized that anyone can contribute without being a "coding ninja."

### DataDeux
#### Speaker: Deepak

Deepak introduced **DateDeux**, a library for advanced calendar operations, including date arithmetic and finding the start/end of months.

---

The meetup ended with engaging talks and valuable learning opportunities for all attendees. 

Meeting minutes contributed by **Suresh**. [Chennaipy Meetup](http://www.meetup.com/Chennaipy/members/4217588/).
