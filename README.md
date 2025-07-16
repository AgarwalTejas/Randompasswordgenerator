# Randompasswordgenerator
Python Secure Password Generator


Objective

To develop a secure and flexible password generator that:
- Ensures randomly created passwords using diverse character sets
- Validates user input for length and complexity
- Offers a GUI for accessibility and ease of use
- Allows copying to clipboard and excludes specific characters for customization

 Key Components & Steps Performed

1.  Randomization
Goal: Generate random characters and strings for secure passwords  
Steps Performed:
- Used random.choice() over specified character sets to build passwords of user-defined length  
Tools Used: random, string  
Outcome: Dynamically creates unpredictable passwords of varying lengths and combinations


 2. User Input Validation
Goal: Ensure proper input for password criteria  
Steps Performed
- Checked for numeric length entry, minimum value thresholds
- Validated selection of character types (e.g., letters, digits, symbols)  
Tools Used: re for input validation, conditional logic  
Outcome: Prevented invalid or weak configurations and ensured robust password generation


 3.  Character Set Handling
Goal: Manage character types for password composition  
Steps Performed:
- Provided toggles for including uppercase, lowercase, digits, and symbols
- Parsed user selection into usable sets  
Tools Used: string.ascii_letters, string.digits, string.punctuation  
Outcome: Customized sets for varied password requirements

 4.  GUI Design 
Goal: Enhance user interaction via graphical interface  
Steps Performed:
- Developed GUI with Tkinter for selecting password criteria and length
- Embedded buttons for generation and clipboard functionality  
Tools Used: Tkinter (built-in Python GUI library)  
Outcome: Clean, accessible interface for users of all skill levels



 Tools & Libraries Summary

 Feature                  Tools Used                         

 Randomization           random, string                 
 Input Validation        re, Python conditional logic     
 Character Sets          string.ascii_letters 
 GUI                     Tkinter                          
 Clipboard               pyperclip or Tkinter clipboard
 Customization           json, GUI controls               



 Outcomes

- Easily generates secure passwords of desired length and complexity
- Helps users avoid weak or repetitive password choices
- Offers intuitive GUI and clipboard copy features
- Provides flexible settings for personalized output


git clone https://github.com/yourusername/password-generator
cd password-generator
pip install -r requirements.txt
python generator_gui.py
