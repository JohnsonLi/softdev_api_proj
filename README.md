Original : https://github.com/taniacao12/slowpokeRodriguez  


# Tuned Recipes

Tuned Recipes is a website that provides recipes tailored to the user's preferences and also recommends music based on the recipe chosen. If the user is registered, their preferences will be saved for future use. While registered users may add recipes, guests will only be able to view recipes and listen to recommended music.

## Getting Started

1. Clone this repo with either ssh or http.
```
$ git clone git@github.com:taniacao12/slowpokeRodriguez.git
or 
$ git clone https://github.com/taniacao12/slowpokeRodriguez.git
```
2. Open your virtual environment
```
$ . <name_of_vEnv>/bin/activate
```
4. Copy api key files to root of project directory. (lastFM_keys.txt, youtube_keys.txt, yummly_key.txt)

3. Run the app.py file with python
```
$ python app.py
```
4. Access the website by going to http://127.0.0.1:5000/ on any browser.

### Dependencies

What things you need to install the software and how to install them:
* Python version - 3.6.6
* Virtual Environment 
* Flask
* Wheel
* Time

### API Access

Requesting an API key from Yummly may take a long time, so you can use ours: 00b049845c3a685d5b88c8217a3335e7

Copy that into a text file named "yummly_key.txt" which should be in the root of the repo. 

### Installing

Installing virtual environment, flask, and wheel.
```
$ python -m venv <name_of_vEnv>
$ . <name_of_vEnv>/bin/activate
(<name_of_vEnv>) $ pip install -r <path-to-file>requirements.txt
```

### Contributors

* <a href= https://github.com/taniacao12> Tania Cao </a>
* <a href= https://github.com/mhowlader> Mohtasim Howlader </a>
* <a href= https://github.com/JohnsonLi> Johnson Li </a>
* <a href= https://github.com/HasifAhmed> Hasif Ahmed </a>
