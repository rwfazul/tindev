# tindev

Tinder for developers!

- [backend](/backend): Node.js REST API
- [frontend](/fronted): React app
- [mobile](/tindev): React Native app

## How to

- Update database (MongoDB Atlas) credentials [here](https://github.com/rwfazul/tindev/blob/master/backend/src/server.js#L19)

- Running backend

```bash
	$ yarn dev # or $ nodemon src/server or $ node src/server 
```

- Running frontend

```bash
	$ yarn start # or $ react-scripts start 
```

- Running mobile (tindev)

```
	$ yarn react-native run-android # run-ios
	$ yarn start # or $ react-native start
	# running on device
	$ adb reverse tcp:3333 tcp:3333
	$ adb reverse tcp:8081 tcp:8081	
```

<hr/>

<p align="right"><em>Devloped during OmniStack 8.0 from Rocketseat</em></p>


