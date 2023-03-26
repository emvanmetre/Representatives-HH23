# RepWrite for HooHacks 2023
Find and contact your representative based on your zipcode!

## RepWrite
RepWrite is an email generator using AI. It helps residents to simply enter their ZIP code along with an issue of interest, then the AI — powered by cohere.ai — writes and sends an email to the representative. 

## Motivation
We created this project because we wanted to make it easier and more accessible for anyone to communicate with their representatives.

## Build Status
RepWrite is currently under development. A demo is available at [elizabethmvm.pythonanywhere.com]   
Currently, RepWrite is only functional for citizens of Virginia.

## Code Style
RepWrite uses python, html, and css.


## Directory
RepWrite/  
| main.py  
| templates/  
  | about.html  
  | contact.html  
  | index.html  
  | representative.html  
| static/  
  | catherine.png  
  | emily.png  
  | elizabeth.png  
  | map.jpg  
  | R-Logo.png  
  | styles.css  
  | va_zips.csv  
  | writing.jpg  

## Installation/Setup
1. Create a new project in PyCharm. NOTE: you will need a virtual environment, venv.
2. Download RepWrite.zip from the main branch of this repository.
3. Open RepWrite folder and drag the contents into your new PyCharm directory. NOTE: make sure to refactor the files and overwrite main.py!!
4. Install any packages listed in the import section of main.py as needed.
5. Run main.py! It will create a local host that you can click to view the site.

## Usage
- Run main.py in communication with html and image sources
- main.py calls functions from flask and cohere to generate output
- Change web pages using .html files in /templates


## Credits
### https://dashboard.cohere.ai/playground/generate
### https://getbootstrap.com/docs/5.3/getting-started/introduction/ 
### https://help.pythonanywhere.com/pages/ 
### https://flask.palletsprojects.com/en/2.2.x/ 


## License
[MIT]
