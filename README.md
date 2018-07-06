# Minimalistic Environment Monitoring on Raspberry Pi

Show Temperature and Humidity data read from DHT11 on a webpage hosted on your Pi.


## Dependencies
- Python 2.7.x
- Flask
- Adafruit DHT11 Library

## Important!
Change the `pin` variable to your GPIO-Pin.

The `index.html` file needs to be in a `templates`-subdirectory, otherwise Flask won't find it!

## Run
`sudo python main.py`

`sudo` is required for GPIO access.