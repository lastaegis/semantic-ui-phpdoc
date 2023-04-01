# semantic-ui-phpdoc
Template for PHPDoc with Semantic UI

## Run Template Via Docker
Semantic-ui-phpdoc can be run with phpDocumentator Docker, use command below:
```
docker run --rm -v <ROOT_WEBSERVER_HOST>:<ROOT_WEBSERVER_DOCKER> phpdoc/phpdoc:3 -d <PACKAGE_TO_DOCUMENTED> -t <DOCUMENTATION_RENDER_LOCATION> --template=semantic-ui-phpdoc/
```