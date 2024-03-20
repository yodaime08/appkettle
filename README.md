# Home Assistant Addons for AppKettle
Clone of : https://github.com/longmover/ha_addons

Some change :
- In Docker file : Add py3-paho-mqtt and py3-pycryptodomex, comment RUN pip install paho.mqtt and pycryptodomex
  because of "he command ‘/bin/ash -o pipefail -c pip install paho.mqtt pycryptodomex’ returned a non-zero code: 1" error
  ( see https://community.home-assistant.io/t/my-first-addon-bring-your-appkettle-back-to-life/551798/16)
- Add section "Configure your MQTT server variables" in DOCS.md
