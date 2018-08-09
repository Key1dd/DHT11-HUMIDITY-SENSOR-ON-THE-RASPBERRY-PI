# DHT11-HUMIDITY-SENSOR-ON-THE-RASPBERRY-PI
HOW TO SET UP THE DHT11 HUMIDITY SENSOR ON THE RASPBERRY PI

PROGRAMMING THE DHT11 WITH PYTHON
We’ll be using the Adafruit DHT11 Python library. You can download the library using Git, so if you don’t have Git installed on your Pi already, enter this at the command prompt:

sudo apt-get install git-core

Note: If you get an error installing Git, run sudo apt-get update and try it again.

To install the Adafruit DHT11 library:

1. Enter this at the command prompt to download the library:

git clone https://github.com/adafruit/Adafruit_Python_DHT.git

2. Change directories with:

cd Adafruit_Python_DHT

3. Now enter this:

sudo apt-get install build-essential python-dev

4. Then install the library with:

sudo python setup.py install

OUTPUT TO AN LCD
To output the DHT11 readings to an LCD, we’ll need to install another Python library called RPLCD to drive the LCD. To install the RPLCD library, we first need to install the Python Package Index, or PIP. PIP might already be installed on your Pi, but if not, enter this at the command prompt to install it:

sudo apt-get install python-pip

After you get PIP installed, install the RPLCD library by entering:

sudo pip install RPLCD

Once the library is installed, you can use the following code to output the DHT11 readings to an LCD:

