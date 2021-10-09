# Geo-hashing-docker

## API to Hash Lattitude and Longitude into a single encrypted string using FastAPI, and convert it to QR Code for more portability. Hosting the API in a Deta Cloud environment.

### Features :
- Geo-coordinates to geohashed string
- Encode (lat,lon) to an encrypted string
- Decode the encrypted string back to coordinates
- Using Fast API, we can make API calls to convert any coordinates to string and decode it back.
- Inbuilt QR Code generation function, to convert encoded string to QR
- Hosted on Deta using CLI

## Docker Installation

- The docker file is generated using the docker cli and this can be connected to heroku or such platforms to host.
