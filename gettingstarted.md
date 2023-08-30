Precisely Data Integration Suite offers different Geo Addressing services that can be used to convert physical addresses into geographic coordinates. These services include address validation, standardization, geocoding, and reverse geocoding.

[Service Description – Geo Addressing - Precisely](https://www.precisely.com/legal/data-integrity-suite-service-information/service-description-geo-addressing)

## Swagger UI

Explore the powerful Data Integrity Suite Geo Addressing APIs to enhance the accuracy and completeness of your location data.
[Precisely DIS API Swagger UI](https://dis-developer.api.cloud.precisely.com/swagger-ui/index.html#/)

## Prerequisites

### Generate API Key and API Secret

#### Steps:
1. In order to generate `{{api_key}}` and `{{api_secret}}` you need to log into [DI Suite](https://cloud.precisely.com/) with the credentials provided to you.

(Screenshot)

2. In the Manage API Key section you can generate the `{{api_key}}` and `{{api_secret}}`.

(Screenshot)

You can save them in your system to get responses from different services provided by Precisely.

### Using Postman

#### Steps

1. Using our Postman collection is the easiest way to use our Data Integrity Suite Geo addressing APIs, you can export the entire collection of services and import it in your Postman.

- Use the following URL to open the Data Integrity Suite Geo addressing collection in the postman in your web browser:

[Postman|Collection](https://nam12.safelinks.protection.outlook.com/?url=https%3A%2F%2Fwww.postman.com%2Fcrimson-meteor-968912%2Fworkspace%2Fprecisely-apis%2Frequest%2F25830357-12690ded-d392-4212-8ff9-09ffdb3a1e9f&data=05%7C01%7CTanha.Talavia%40precisely.com%7C4deab3c1e4a2492c596008db15ced9eb%7Cc0a2941c29154bcaaa4ce8880dc77f7f%7C0%7C0%7C638127750443586783%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C3000%7C%7C%7C&sdata=2J3UyfAK8ZJECrG5gzwqHiFVjTa%2Fmih%2Fp9zNt7b9mmE%3D&reserved=0)

- Now you can export the collection from the web browser
- Now you have the Data Integrity Suite Geo Addressing collection in your Postman.
2 Now you need to add the values of the `{{api_key}}` and `{{api_secret}}` to the variables CURRENT VALUE in the collection and save it.

           If you don’t have the values already generated you can use our documentation to generate the {{api_key}} and {{api_secret}} values.
3. Now you can Generate Token.

           Here you can see we have added the value from variables in {{api_key}} and {{api_secret}}, so we don’t need to update the values here, it will always have the updated values from the variables which we set.

           Also note that this token expires in ~60 minutes.