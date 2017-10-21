# eventbrite_digitalsign

A digital sign using chromium web browser to load the Make Haven's eventbrite page.  Using the extension TamperMonkey, we are removing certain navigation and branding elements and modifying the CSS to better suite a digital sign.

To auto launch chromium during startup, edit the following file:
/home/pi/.config/lxsession/LXDE-pi/autostart

Then add the following line to the end of the autostart file:
@chromium-browser --incognito --kiosk https://www.eventbrite.com/o/makehaven-9268848926

