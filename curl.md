# Normal request
curl http://google.com/

# Demand more data
curl http://google.com/ -v

# Generate post request
curl --request POST http://google.com

## passing params 
curl --header "Content-Type: application/json" --request POST --data '{"author": "james", "title":"book"}' http://google.com -v

# Delete request
curl --header "Content-Type: application/json" --request DELETE http://google.com/:id -v

