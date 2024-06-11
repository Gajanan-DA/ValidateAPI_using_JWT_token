Please find the below steps to call the functions in sequences using postman - 

1. https://localhost:44393/api/login/test




2. curl --location 'https://localhost:44393/api/login/login' \
--header 'Content-Type: application/json' \
--data-raw '{
    "Username":"gajanthate",
    "Password":"Test@123"
}'




3. curl --location 'https://localhost:44393/api/login/values' \
--header 'Authorization: Bearer ***********************************************************'




4. curl --location 'https://localhost:44393/api/login/validatetoken' \
--header 'Content-Type: application/json' \
--data '"***********************************************************"'
