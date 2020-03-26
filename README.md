# SSW-345
Stevens Institute of Technology SSW 345 (Modeling and Simulation)

## Homework 4 

### POST /share

Sends a json object to the server and replies with a link where the object can be retrieved.

`body`
```json
    ...some json object you want to store
```

`response`
```json 
{
    "success": true,
    "link":"http://localhost:3000/<uid>"
}
```

### GET /share/:id

Retrieves and deletes a previously sent json object by its unique id.

`response`
```json
    ...some json object you previously stored
```

