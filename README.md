# FakeRESTAPI-ATBH-postman-tests
How to run Postman collection,

1.Open Postman,

2.Import collection and environment : Click "Import", Select the files: FakeRestAPI.postman_collection.json, FakeRestAPI.postman_environment.json, ,

3.Select environment: In the top right corner, choose the imported environment, ,

4.Set environment variables: Click enviornments under the collections and press on FakeRESTAPI Enviornment and enter :, ,

 baseurl = https://fakerestapi.azurewebsites.net/api/v1
If fields show "Enter value", manually enter the value and click Save,

5.Run requests: Right-click the collection → Run,

6.View results: Check response status codes (200, 404, etc.), Check test results (Pass / Fail) in the Tests tab
