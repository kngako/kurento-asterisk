[![logo](https://webrtc.ventures/wp-content/uploads/2017/01/webrtc-logo.png)](https://webrtc.ventures)

# Integration of Kurento with Asterisk

## Software Dependencies

The project requires a running and correctly configured implementation of the following:
1) Kurento Media Server 6.6.0
2) Asterix Server (TODO: WRITE VERSION NUMBER HERE)
3) TURN SERVER

## Node Dependencies

The package.json file should contain an updated list of all the packages being used to get this to work. If you add a package please remember the --save argument. To make sure all the required packages are installed run:

```
npm install
```

### Node Configuration

Set the correct values in the config/default.json or the config/development.json or config/production.json depending on which value you set for your NODE_ENV on your machines environment variables.

## Running the Program
Use the following command to run the thing:
```
npm start
``` 

If everything goes well you should be able to access this via a WebRTC compatible browser: 

```
https://localhost:8443/
```

###### To learn more about this work visit our post blog: [Kurento and Asterisk: a powerful couple](https://webrtc.ventures/2017/02/kurento-asterisk-powerful-couple/)
