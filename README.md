
# Aya-tork's Best Buy APIs automation tests
A simple automated tests example for Best Buy APIs.
# Setup
 1. install postman
 2. import collection
 "*Api Automation/Best Buy.postman_collection.json*"
 3. import environment
 "*Api Automation/workspace.postman_globals.json*"
 4. To run tests: select the imported collection in Postman, click options button and select "**Run collection**".

# API Automation Cases
----------API[1] List products---------
1. validate status code
2. validate response scheme
3. assert that response limit value should be equal to response data count
4. validate content type

----------API[2] Create new category------
1. validate status code
2. validate response scheme
3. assert that updatedAt date should be equal to createdAt date
4. validate content type

