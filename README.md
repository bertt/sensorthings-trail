sensorthings-trail

Shows a trail of SensorThings locations in Leaflet map. 

Demo url: <a href="https://bertt.github.io/sensorthings-trail/ ">https://bertt.github.io/sensorthings-trail</a>

Default thing = 184, to request other thing_id use parameter 'thing':

Trail user thing_id= 185: https://bertt.github.io/sensorthings-trail?thing=185

Demo user aanmaken:

```
curl -X POST \
  https://gost.geodan.nl/v1.0/Things \
  -H 'Content-Type: application/json' \
  -d '{
    "name": "Pietje Puk",
    "description": "Pietje Puk"
}'
```
