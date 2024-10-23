# Using the Homebridge-gsh beta environment

Before completing this setup, you will need to provide to me your `Google Home` login/email, so I can enroll your account in the Beta service. Please use the Homebridge discord server and direct message/chat to share this.

Please note, configuring the beta environemnt will require you to remove your existing Homebridge Google Smart Home configuration, so I you have a setup you don't want to redo, don't do this.

1 - In the homebridge UI under Plugins, disable `Homebridge Google Smart Home` in the homebridge UI

2 - Unlink the `Homebridge` action in the Google Home app

- Settings -> Services -> Works With Google -> Homebridge ( Should be at the top of the screen ), unlink account

3 - In the Homebridge UI under Plugins, search for `GSH` and install `Homebridge Gsh Beta` - current version is v3.0.4, and install

4 - Afer installing, the Homebridge UI should display a `LINK ACCOUNT` button, click this

5 - A pop up window should appear, please note that the Title should be `Homebridge Beta`

- Select your account provider, either github or google
- Authenticate your account
- And confirm the linkage

6 - The Homebridge UI screen should now show that your account was linked

7 - Enter any additional settings you require, and `Save`

- Please do not unclick the Beta option

8 - Restart homebridge as needed

9 - In the `Google Home` app go to Devices, and select the `+ Add` bubble

- Then select `Service`, `Works with Google`
- Under Add new, the beta service should appear `[test] Homebridge Beta`, select it

10 - A window should appear `Homebridge BETA GSH Google Connection`, and select the same account provider / account you selected earlier.

- Authenticate your account

11 - After a few seconds a screen `Choose Device` will appear. You can use the `X` in the top left corner to skip if you want.

## Additional notes

For some reason, in my configuration I need to restart the GSH plugin, and unlink and re-link in the google home app for all my devices to appear.

# Adding Test Users from Google Actions Console

https://developers.home.google.com/cloud-to-cloud/test#share-access

In step 3, Add has been renamed to `Grant Access`
