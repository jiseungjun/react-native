# Init
> npm install -g expo-cli

> expo init **Project Name**

# Start
> expo start

# Build
> expo build:android

> expo build:ios

> expo eject

- It seems your assets have not been optimized yet.
? Do you want to optimize assets now? Yes

- Running this command will overwrite the original assets.
? Do you want to save a backup of each file? (Y/n)

# Error
- Your project must have an Android package set in app.json
See https://docs.expo.io/versions/latest/distribution/building-standalone-apps/#2-configure-appjson

- Error: Problem validating fields in app.json. See https://docs.expo.io/versions/v32.0.0/workflow/configuration/
 • Field: android.package - 'android.package' should be a reverse DNS notation unique name for your app. For example, host.exp.exponent, where exp.host is our domain and Expo is our app. The name may only contain lowercase and uppercase letters (a-z, A-Z), numbers (0-9) and underscores (_). Each component of the name should start with a lowercase letter..
Invalid format of Android package name (only alphanumeric characters, '.' and '_' are allowed, and each '.' must be followed by a letter)
A
ll your files are listed in the file explorer. You can switch from one to another by clicking a file in the list.
