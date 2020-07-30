# Integration Flow Recipes
\| [Browse by Topic](../readme.md)  \| [Browse by Author](../author.md) \| Browsing by Artefact Type \| [Request a Recipe](https://github.com/SAP-samples/cloud-integration-flow/issues/new?assignees=&labels=Recipe%20Request&template=recipe-request.md&title=How+to++) \| [Report a broken link](https://github.com/SAP-samples/cloud-integration-flow/issues/new?assignees=&labels=documentation&template=bug_report.md&title=Broken%20Link) \| [Contribute](https://github.com/SAP-samples/apibusinesshub-integration-recipes/blob/master/CONTRIBUTING.md) \|

## Artefact Type
* [Groovy Scripts](#groovy-scripts)
* [Integration Adapters](#integration-adapters)
* [Reusable integration flows](#reusable-integration-flows)
* [Sample integration flows](#sample-integration-flow)
* [XSLT Scripts](#xslt-scripts)

****

### Groovy Scripts
Recipe|Description|Topic
---|---|---|
[Accessing keystore artifacts using a Groovy script](AccessTenantKeystoreusingScript) |Any keypair available in tenant keystore can be accessed programmatically from a script with the help of the getKey and getCertificate api of the KeyStoreService class|[Security](../readme.md#security)|
[Accessing Partner Directory entries from within a Groovy script](Accessing-Partner-Directory-entries-from-within-a-script)|The String and Binary parameters from the Partner Directory can be accessed using a script with the help of getParameter API of the PartnerDirectoryService class. | [Partner Directory](readme.md#partner-directory) |
[Accessing Value Mappings from Groovy script](AccessValueMappingsDynamicallyScript)|Use ```ITApiFactory.getApi()``` to get ```ValueMappingAPI``` class that can be used to retrieve the mappings.|[Mappings](../readme.md#mappings)|
[CMS Decryption with AES256-GCM algorithm using iaik libraries](Decryption_using_AES_GCM_iaik)|Decryption algorithm AES256-GCM using iaik which is the default security provider for CPI|[Security](../readme.md#security)|
[Encryption with AES256-GCM algorithm using iaik libraries](Encryption_using_AES_GCM_iaik)|Encryption algorithm AES256-GCM using iaik which is the default security provider for CPI|[Security](../readme.md#security)|
[Generate AWS4-HMAC-SHA256 Signature](GenerateAWS4_HMAC_SHA256)| A reusable recipe to generate an AWS specific AWS4-HMAC-SHA256 signature and pass it as a HTTP Authorization header.|[Amazon Web Service](../readme.md#amazon-web-service)\|[Security](../readme.md#security)|

****

### Integration Adapters
Recipe|Description|Topic
---|---|---|
[Build custom Redis integration adapter](redis-integration-adapter/readme.md)|Redis is advanced key-value store where keys can contain strings, hashes, lists, sets and sorted sets. In addition it provides pub/sub functionality for inter-app communications. This integration adapter allows an integration flow to access Redis.| [Integration Adapters](../readme.md#integration-adapters)|
[Build custom Rabbit MQ integration adapter](rabbitmq-integration-adapter/readme.md)|The rabbitmq: component allows you produce and consume messages from RabbitMQ instances. Using the RabbitMQ AMQP client, this component offers a pure RabbitMQ approach over the generic AMQP component. This integration adapter enables an integration flow to persist or read messages in a RabbitMQ queue. | [Integration Adapters](../readme.md#integration-adapters)|
[Build custom MongoDB integration adapter](mongodb-integration-adapter/readme.md)|MongoDB is a very popular NoSQL solution and the camel-mongodb component integrates Camel with MongoDB allowing you to interact with MongoDB collections both as a producer (performing operations on the collection) and as a consumer (consuming documents from a MongoDB collection). This integration adapter enables an integration flow to connect to MongoDb collection.| [Integration Adapters](../readme.md#integration-adapters) |

***

### Reusable Integration flows
Recipe|Description|Topic
---|---|---|
[Generate AWS4-HMAC-SHA256 Signature](GenerateAWS4_HMAC_SHA256)| A reusable recipe to generate an AWS specific AWS4-HMAC-SHA256 signature and pass it as a HTTP Authorization header.|[Amazon Web Service](../readme.md#amazon-web-service)\|[Security](../readme.md#security)|

***

### Sample integration flows
These recipes only have sample integration flows, other types usually **also** have samples included.

Recipe|Description|Topic
---|---|---|
[Connect to Amazon DynamoDB](ConnectToAWSDynmoDB)|SAP CPI needs to make a rest call to DynamoDB endpoint|[Amazon Web Service](../readme.md#amazon-web-service) \|[Database](../readme.md#database)|

***

### XSLT Scripts
Recipe|Description|Topic
---|---|---|
[Convert JSON to XML using XSLT Mappings](ConvertJsonToXMLusingXSLT30)|This recipe converts and incoming file in JSON format into XML format |[Mappings](../readme.md#mappings)|
[Use Map data structures in XSLT Mapping](ConstructMapDataStructsUsingXSLT30)|Utilize [Map](https://www.w3.org/TR/xslt-30/#map) data structures in XSLT Mappings flow step.|[Mappings](../readme.md#mappings)|
[Invoke Java functions from XSLT Mapping](InvokeJavaFunctionsFromXSLT30)|Writing reflexive extension functions in Java to be invoked from XSLT Mappings | [Mappings](../readme.md#mappings) |

***
