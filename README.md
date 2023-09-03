## Test project: "My sensors"
### Purpose:
Data gathered from multiple sensors managed by ESP32 cards, published to a MQTT broker and served to a secure Flask web app suscribed to them.
### Design: 
User &larr;&rarr; Flask Web App (secure) -[subscribe]&rarr; MQTT broker  &larr;[publish]- Arduino program (ESP32+sensors)




