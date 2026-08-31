Hydro Farm - Mobile First starter
Pages: Home, Data, Control, Growth, Alerts, Settings.
Growth is local-only and independent from ESP32. pH/EC logs are manual only.
Initial MQTT topics: hydroponic/#, hydroponic/control, hydroponic/config.
IMPORTANT: match MQTT payload/topics with the final ESP32 firmware before production. Do not distribute an admin MQTT password in a client APK; use a restricted account.
