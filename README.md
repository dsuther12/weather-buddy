# Weather Buddy

Weather Buddy is a Python application that is used to get weather data from anywhere around the world.

## Usage
To use Weather Buddy, simply run the Python script. You will be prompted to enter a location in which you want to know weather data for. Once you enter a location, a menu will display that asks which weather info you would like to know. Once prompted, type the number of the menu item you would like to select, E.g. type 1 to get current weather forecast. The program has functionality to choose different menu items after one has been selected, so the program does not need to be rerun to search for new data.

## Where is data gathered from?
The data used in this application is scraped from [www.weather.com](www.weather.com) using the selenium and BeautifulSoup Python libraries.

## Notes
- If the program does not prompt on first run, try interrupting it and trying again.
- If an error occurs after selecting a menu item, please rerun the program and try again. There is a chance you entered an invalid location in the prompt.
