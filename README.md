# Objectives
Workbook on how to build a **Home Automation solution**, running on a **Raspberry Pi with openHABian and openHAB2**.

## As an openHAB Beginner
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

## Links
This guide is also published [here](https://community.openhab.org/t/make-project-home-automation/38613) on the openHAB forum.

## Warrenty
THIS DOCUMENT IS PROVIDED BY THE AUTHOR "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
