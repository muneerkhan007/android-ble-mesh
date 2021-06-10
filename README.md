
BE Mesh: A Bluetooth Low Energy Mesh Network

# Create a Be Mesh!

1. [Download](https://play.google.com/store/apps/details?id=it.drone.mesh) and open the app
2. Press the start button
3. Chat with the others
4. Try to send an email or a tweet


# Build the app from source

Please note that the current version of the repository does not reflect the version onthe google play store and compatibility between versions is not guaranteed.


## Pre-requisites

- The phone candidate to be server must support multipleAdvertisement
- Android SDK >= 23
- Compatible with Android Things!


- Clone this repository
- You must create two files in *app/src/main/resources* with the following attributes:

   **email.properties:**


```
email.username=
email.password=

```    
    
   **twitter4j.properties:**

```
debug=true
oauth.consumerKey=
oauth.consumerSecret=
oauth.accessToken=
oauth.accessTokenSecret=
```

- Build the project and launch the app on your smartphone 
