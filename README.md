# philips_js_2k16

This is a Updated Version for Home Assistant for USE With 2016 Models

Differences Between the Joint Space Versions

2k16 Uses :
HTTPS over port 1926 instead of 1925 which requieres basic http authentication aswell
They Removed the Channels And Sources Feature atleast i couldn't get it to work for now

this makes it somewhat useable in homeassistant

notes :
Device State Is always ON
Volume Adjust Does Work
Standby Does Work

# Install :
cp ./__init__.py ~/.homeassistant/deps/haphilipsjs/
cp ./philips_js.py /usr/lib/python3.5/site-packages/homeassistant/components/media_player/

Or into what ever folder your hass is located
