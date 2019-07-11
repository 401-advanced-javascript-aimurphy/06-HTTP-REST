# LAB - 06

## Simple API - HTTP and REST

### Author: Ai 

### Links and Resources
* [submission PR](https://github.com/401-advanced-javascript-aimurphy/simple-api/pull/3)

#### Documentation
* [api docs](https://app.swaggerhub.com/apis/aimurphyii/lab6/0.1#/default/get_products_) (API servers)
* [jsdoc](http://xyz.com) (Server assignments)
* [react sandbox](https://codesandbox.io/s/api-client-c8jkw) (React assignments)


###### `post on CLI`
* post:
`echo '{"id": 1, "description":"describe it","display_name": "name it", "name":"real name"}' | http post :3000/categories`


### Setup
#### `.env` requirements
* `REACT_APP_API_SERVER=http://localhost:3000`

#### Running the app
* `json-server --watch data/db.json`
* Endpoint: `/products/`
  * Returns a JSON object of product schema.
* Endpoint: `/categories/`
  * Returns a JSON object of category schema.
  
#### Tests
* Testing done using the swagger.io website, you can use tools to play and try it out
[click here to go there](https://app.swaggerhub.com/apis/aimurphyii/lab6/0.1#/default/get_products_)

#### UML
![uml](https://github.com/401-advanced-javascript-aimurphy/simple-api/blob/master/img/IMG_7638.jpg?raw=true)
