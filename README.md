# Nudity-Detector-API
This is a Nudity Dectector API which takes the input as a Single url or Multiple url and returns a if the image is safe or not(in terms of NSFW content).

### For Multiple URLS
curl -X POST -H "Content-Type: application/json" -d "{\"urls\": [\"https://i.pinimg.com/474x/82/91/2a/82912ac6bc738e240506cc018f51be7d.jpg\", \"https://i.pinimg.com/originals/87/c6/8f/87c68fd11bc894704dd891a3c8c342cd.jpg\", \"https://media.geeksforgeeks.org/wp-content/uploads/geeksforgeeks-6.png\"]}" http://localhost:5000/api/batch

### For Single URL
curl -X GET -H "Content-Type: application/json" http://localhost:5000/api/single?url=https://i.pinimg.com/originals/87/c6/8f/87c68fd11bc894704dd891a3c8c342cd.jpg

###Note: 
1. If running code on Google Colab: change localhost:5000 with server_address.ngrok.io (provided by google colab).
2. Link contains inapproiate image.

### Future Scope:
- Creation of Browser Extension.
