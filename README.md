# toggle-feature

# Url in Postman 

# this is the get url 
curl --location 'http://localhost:8765/orders'

# this is the post url for togglz enabling

curl --location 'http://localhost:8765/actuator/togglz/DISCOUNT_APPLIED' \
--header 'Content-Type: application/json' \
--data '{
"name": "DISCOUNT_APPLIED",
"enabled": true
}'


# togglz enable url for web - ui
http://localhost:8765/togglz-console/index



