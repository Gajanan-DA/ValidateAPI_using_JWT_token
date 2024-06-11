Please find the below steps to call the functions in sequences using postman - 

1. https://localhost:44393/api/login/test




2. curl --location 'https://localhost:44393/api/login/login' \
--header 'Content-Type: application/json' \
--data-raw '{
    "Username":"gajant",
    "Password":"Test@123"
}'




3. curl --location 'https://localhost:44393/api/login/values' \
--header 'Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJHYWphbmFuIFRoYXRlIiwiZW1haWwiOiJ0ZXN0LmJ0ZXN0QGdtYWlsLmNvbSIsIkRhdGVPZkpvaW5nIjoiMjAyMC0wNi0xMSIsImp0aSI6IjJmNDZkYmZjLWZiNTgtNGViMi05YmM3LTZhYjVlZGVkZjE2MyIsImV4cCI6MTcxODEwMDc2OCwiaXNzIjoiVGVzdC5jb20iLCJhdWQiOiJUZXN0LmNvbSJ9.qHBKVMDppzFJRst_6kt8rdwB-vbGiFObv5GV9RdZ-gc'




4. curl --location 'https://localhost:44393/api/login/validatetoken' \
--header 'Content-Type: application/json' \
--data '"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJHYWphbmFuIFRoYXRlIiwiZW1haWwiOiJ0ZXN0LmJ0ZXN0QGdtYWlsLmNvbSIsIkRhdGVPZkpvaW5nIjoiMjAyMC0wNi0xMSIsImp0aSI6IjQ5OWE5NGU0LTJjMTAtNDdlMi04MmIzLWI4NWEzMDhhMDU3NyIsImV4cCI6MTcxODEwMTc5NCwiaXNzIjoiVGVzdC5jb20iLCJhdWQiOiJUZXN0LmNvbSJ9.9T0WlA61D9WbCPWkl6g7AhnkqN5iO3lcAA8kkUIVk5I"'