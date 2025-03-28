Title: Minutes of Meetup - 23 Nov 2019
Date: 2019-11-23 16:00
Tags: Meeting Minutes
Summary: The November 2019 Chennaipy meetup included talks on **Embedded Testing with Robot Framework**, **Teaching Kids Python the Scratch Way**, and **Data Compression Techniques using Python**.

# ChennaiPy November 2019 Meetup - Meeting Minutes

The meetup took place on **November 23, 2019** at **Chennai**.

---

### Talk 1: Embedded Testing with Robot Framework
**Speaker:** Rengaraj D

- **Problem Statement**: Automating the testing of an **intruder detection alarm system**.
- **Components**:
  - **TI Programmable Microcontroller**: Used in the system under test.
  - **Reed Switch**: Detects if the door is open.
  - **Multicolor LED**: Used as an output indicator.
- **Demo**:
  - Automated testing using **Energia electronics prototyping IDE** and **Robot Framework**.
  - The initial test failed due to a bug in the intruder detection logic.
  - After fixing the bug, the tests passed successfully.
- **Test Case Modelling**:
  - Ensuring system initialization to avoid false positives or negatives in test cases.
  - Using **GPIO Python interface** for simulating inputs and reading outputs.
  
  [TI Microcontroller](https://www.ti.com/tool/MSP-EXP430FR2355)  
  [Reed Switch Info](https://www.explainthatstuff.com/howreedswitcheswork.html)  
  [Energia IDE](https://energia.nu/)  
  [GPIO Python Interface](https://www.raspberrypi.org/documentation/usage/gpio/python/README.md)

---

### Talk 2: Teaching Kids Python the Scratch Way
**Speaker:** Vijay Kumar

- **Scratch**: A programming interface to help young people think creatively.
- **Demo**:
  - Animated a ball bouncing around the corners of a box.
  - Created a program that emulated a paddle and bouncing ball.
- **Scratch Programming**: Easy for kids to learn with systemic thinking.
- **Python VM**: Vijay created a Python VM to run disassembled Scratch programs, transforming kids' Scratch abilities into Python programming.
- **Scratch2py**: Allows Python code to coexist with Scratch programs, bridging the gap between Scratch and Python.

  [Scratch](https://scratch.mit.edu/projects/editor/?tutorial=getStarted)  
  [Scratch2py GitHub](https://github.com/bravegnu/scratch2py)

---

### Talk 3: Data Compression Techniques using Python
**Speaker:** Ashok G

- **History**: Data compression is influenced by early inventions like **Morse code** and Claude Shannon’s work in **Information Theory**.
- **Need for Compression**: Essential in **Machine Learning** and **Deep Learning** to minimize storage and transmission costs.
- **Huffman Encoding**: Explained how it reduces the size of text data using probability calculations to assign shorter codes to more frequent characters.
- **Wireless Transmission**: Emphasized the need for data compression to make better use of the transmission medium (air).

  [Shannon's Paper](https://en.wikipedia.org/wiki/A_Mathematical_Theory_of_Communication)  
  [Huffman Coding](https://www.techiedelight.com/huffman-coding/)

---

The meetup concluded with interesting discussions and a networking session.

Meeting minutes contributed by **Saravanan K**.
