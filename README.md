# HTML

Vaishak Menon

## Repository to show my HTML Progress/Experience

Technologies used thus far:

- VSCODE
- HTML
- Markdown
- Git

VSCode Simple Browser Web Address: http://127.0.0.1:5500/root/index.html

## NOTES- What I Have Learned

\<!-- COMMENT TAG -->

File name expected to launch a website: index.html  
Try to name using lowercase with no spaces  
validator.w3.org: Website for validating HTML code  
Code was run through validator.w3.org:

Immediate first errors:

- Consider adding a lang attribute to the html start tag
- Character encoding was not declared
- Start tag was seen without seeing a doctype first

"\<html>" is a tag  
"\<html>\</html>" considered an element;  
definition includes everything from starting tag
information contained, ending tag  
Tag and element are often interchanged  
head is the metadata tag; information not seen on website

### **LESSON 1 CHANGES AND VALIDATION RESULTS**

- Adding "\<!DOCTYPE html>" Must have for all html files
  - FIXES DOCTYPE ERROR
- Adding "\<html lang="en">" -US or -GB are also options
  - FIXES LANG ERROR
- Adding "\<meta charset="utf-8">" specifically 1024 bytes after beginning of document
  - FIXES CHARACTER ENCODING ERROR

### **LESSON 2 CHANGES AND VALIDATION RESULTS**

Typical meta tags that contain metadata for the page

- Added data to metadata such as name author and description
- Used link tag to add favicon and sample stylesheet
- Created File Structure for future lesson use

After validating, no errors

### **LESSON 3 CHANGES AND VALIDATION RESULTS**

body tag; part that everyone sees

Worked in the body tag

- Used hr and br (horizontal line and line break)
- Generally only have 1 "h1" tag
- As many "h2", "h3", "hn" tags as you wish
- General text or paragraphs go in the "p" tag
- Formatting:
  - "em": Italics
  - "strong": Bold
  - abbr: Abbreviations
  - & is used for escaping or specific characters
  - address: Specifically used for addresses, auto-italicizes

After validating, no errors

### **LESSON 4 CHANGES AND VALIDATION RESULTS**

List Types

Created three lists
"li": List Item

First: Ordered list

- Uses "ol" and "li"
- Starts at 1, has a little period at the end

Second: Unordered List

- Uses "ul" and "li"
- Creates a little dot
- This page has extra space for the
  unordered list as the <p> tags were kept

Third: Description List

- Uses "dl"
- Description term; Topic; "dt"
- Description details: Details; " dd"

After validating, no errors

### **LESSON 5 CHANGES AND VALIDATION RESULTS**

Created an About Me page  
About Me page is used to demonstrate the usage of "#" and "/"

- "#" is used for return to nav element
- "/" is used for return to a original page

Links:

Absolute Links: Give direct path  
Relative Links: Give relative path  
Link Modifications: Add additional information to end of href
Examples:

- download to download a file
- target="\_blank" for new page

Link Rules:

- Avoid printing the full web address to the page
- Avoid "links to" phrase
- Keep text short; Exact topic, not sentences.
- No links that say "click here".

After validating, no errors
