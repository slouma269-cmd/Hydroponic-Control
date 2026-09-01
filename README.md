# Hydroponic Control — Final

Mobile-first GitHub Pages/WebView app for GH001.

- Firebase Email/Password + Firestore
- HiveMQ Cloud WebSocket
- Arabic/English/French; Arabic default and RTL
- Light/Dark/System
- Home gauges: Air Temperature, Humidity, Water Temperature, Water Level, pH, EC
- Data charts 1H/6H/24H/7D
- Control: Pump 1 NFT, Pump 2 Venturi, Pump 3 tank fill, Pump 4 Pad Cooling, Fan 1, Fan 2
- Manual confirmation and safety block for Pump 3 / Pad Cooling manual ON
- Growth groups with leafy/fruiting templates, editable stages, seed date, reminder time, daily pH/EC before/after, harvest and PDF
- Firebase cloud persistence for app settings and growth records
- MQTT topics: hydroponic/GH001/{sensors,state,config,config/state,command,ack,availability}
- Browser/Android notification API support

MQTT WebSocket: wss://99580666d99a4632b4a1d5087e22d494.s1.eu.hivemq.cloud:8884/mqtt
Username default: hydro_app
The MQTT password is entered once in Settings and stored locally; it is not sent to Firebase.
