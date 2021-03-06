# Covid-19 Visualization around Namibia
 Developing automatic dashboards which allows users to query and customize visualisations with dash and flask

## Preparation
- In the project folder, create a folder `dataset/raw/` and place your `xlsx` data files there.

## Running the program
#### NB: Any line that starts with `$` indicates that the following text should be executed in the terminal/CMD prompt.

- Open up the Terminal or CMD, navigate to the `covidVisuals` directory location (replace <ins>folder/folder</ins> with the correct location) by...

      $ cd folder/folder/covidVisuals
      
- Install pip3

      # Linux
      $ sudo apt-get install python3-pip

- Install virtualenv
      
      # Linux
      $ sudo apt-get install virtualenv
      
      # Mac OS
      $ sudo -H pip install virtualenv
      
      # Windows
      $ pip install virtualenv
  
- Create a virtual environment
  
      # Mac OS / Linux
      $ virtualenv -p python3 venv

      # Windows
      $ python3 -mvenv venv
      
- Activate the environment
  
      # Mac OS / Linux
      $ source venv/bin/activate
      
      # Windows
      $ venv\Scripts\activate

- Install the requirements.txt

      # openpyxl is a dependency for Pandas
      $ pip install openpyxl
  
      # Mac OS / Linux
      $ pip3 install -r requirements.txt
      
      # Windows
      $ python3 -m pip install -r requirements.txt
    
- Run the script...

      $ python3 app.py

- Click the localhost link to view the webpage


### Installing or updating packages

- Go to folder

      $ cd folder/folder/covidVisuals

- Activate env

      # Mac OS
      $ source venv/bin/activate

      # Windows
      $ venv\Scripts\activate
  
- Install or update package

      # specific command

- Update *requirements.txt*

      $ pip freeze > requirements.txt

# Resources

### LIVE WEB APP HOSTED ON HEROKUAPP

- https://covidnamibia.herokuapp.com/

### Inspiration
- https://realpython.com/python-dash/

### Deploying to heroku
- https://www.youtube.com/watch?v=b-M2KQ6_bM4&ab_channel=CharmingData
- https://github.com/Coding-with-Adam/Dash-by-Plotly/tree/master/Deploy_App_to_Web/Heroku_App
