# ha-pcf8574

this is an Home Assitant Integration for the I2C 8 bit bus expander PCF8574. 

before that I've tried a pull request that was denied later
https://github.com/home-assistant/core/pull/53821

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=aSauerwein&repository=ha-pcf8574&category=integration)

## hassio on raspberry pi

to use the i2c ports on a rasppbery we have to enable i2c bus first.  
the easiest way to to this is by using the
https://community.home-assistant.io/t/add-on-hassos-i2c-configurator/264167

after installing the addon repository you also need to enable the advanced mode in Home assistant, otherwise the addon is just non shown in the addon store. 
to enable advanced mode click on your profile icon and enable advanced mode. 

the default bus addess is "1" and most of the pcf8574 use eitehr 0x20=32 or 0x21=33 as i2c address. 
