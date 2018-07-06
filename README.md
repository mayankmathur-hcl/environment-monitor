# Minimalistic DHT11 Display on Raspberry Pi

Easily show your DHT11 Temperature and Humidity data on a webpage hosted on your Pi.


## Dependencies
- Python 2.7.x
- Flask
- Adafruit DHT11 Library

## Important!
Change the `pin` variable to your GPIO-Pin (see http://robintemme.de/Pi.html for reference).

The `index.html` file needs to be in a `templates`-subdirectory, otherwise Flask won't find it!

## Run
`sudo python main.py`

`sudo` is required for GPIO access.