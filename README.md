# imageUpload
image upload using Python story 1

upload image using postman, inport the json img.postman_collection.json at api folder

api.py
------
uploaded file will be stored at uploads folder
after it passed file format validation, it will be moved to /static/upload folder
a uniqueidentifier will be return for permanant image link

image.py
--------
open a browser
enter this url http://127.0.0.1:5000/?image=123
replace 123 with the uniqueidentifier you receive from upload file response

unit testing test/test_upload.py
--------------------------------
added 2 test cases for valid file format and invalid file format






