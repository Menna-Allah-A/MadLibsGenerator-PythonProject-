# Mad Libs Generator  

A Python script that creates fun, user-customized Mad Libs stories!  

## Features  
- Reads a story template from a text file (`Story.txt`).  
- Dynamically identifies placeholders (e.g., `<adjective>`, `<noun>`).  
- Prompts users to input words for each placeholder.  
- Generates and displays the completed story.  

## How It Works  
1. Place your story template in `Story.txt` with placeholders (e.g., `"The <noun> jumped over the <adjective> moon."`).  
2. Run the script (`MadlipsGenerator.py`).  
3. Enter your chosen words when prompted.  
4. Enjoy your custom Mad Libs story!  

## Technologies  
- Python (File I/O, String Manipulation, Dictionaries)  

## Example  
```plaintext
Story.txt: "The <noun> ate a <adjective> <food>."  
User inputs: "dragon", "spicy", "taco"  
Output: "The dragon ate a spicy taco."  
