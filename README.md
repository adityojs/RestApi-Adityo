# RestApi-Adityo
server.address=localhost
server.port=8081

# mysql
spring.datasource.url=jdbc:mysql://localhost:3306/SampleController
spring.datasource.username=root
spring.datasource.password=root

http://localhost:8081/external/services/rest/sample-service
POST
{

  "sampleservicerq": {

    "service_id": "20200421201455122",

    "order_type": "PRO",

    "type": "20221120233514",

    "trx_id": "c6714ec0-b379-11e9-889b-7f7167f4f72d"

  }

}
