# Objectives
Guide on how to build a **Home Automation solution**, running on a **Raspberry Pi with openHABian and openHAB2**.

As an openHAB Beginner
* The main goal is to learn openHABian & openHAB2.
* Get a Home Automation solution up & running and extend.
* There might be better solutions for things shared – but the solution works fine so far.
* Getting motivated to develop more with openHAB.

## Functions
*	Display temperature & humidity measured in living room, basement & garage.
*	Display weather information obtained from the OpenWeatherMap service. 
*	Charts for selective weather items, room temperature & humidity.
*	Display Astro data sun rise, sun set, daylight duration, moon phase and other info.
*	Control Somfy roller shutters with RTS motors in living room and bed room.
*	Philips Hue Lighting System control via Hue Bridge for ZigBee devices.
*	Security door & window wireless contact detectors.
*	Energy Power Consumption metering from “volkszaehler” with charts.
*	Homepage counter with chart.
*	Raspberry Pi system information with charts and threshold email notification.
*	MQTT subscribe & publish messages to trigger actions or information.
*	Add more features whilst developing  ...

## Explore How To
*	Setup & configure openHABian & openHAB2.
*	Use the RFXCOM RFXtrx USB RF Transceiver (RFXtrx433E) for
o	Temperature & Humidity devices.
o	External Wind device (only for RFXCOM tests).
o	Other 433Mhz devices, i.e. door contact
*	Use external services, i.e. OpenWeatherMap.
*	Use actions, i.e. MQTT messaging.
*	Use bindings like MQTT, Astro, Philips Hue.
*	Use Node-RED as an alternative rules engine.
*	Use the openHAB Android App (native client).
*	Create advanced User Interfaces, i.e. HABPanel & Node-RED.

## Approach
*	Setting up the Raspberry Pi, RFXCOM with connected devices, Somfy roller shutters and other devices. Use the Paper UI for Binding, Things, Channel configuration.
*	Create the Basic UI textual configuration files including rrd4j charts & MQTT. 
*	Planned UI’s HABPanel & Node-RED (later stage, not included in this document)


