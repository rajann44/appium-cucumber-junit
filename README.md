# appium-cucumber-junit
Appium, Junit, Cucumber, Java

#How to get bundle id of iOS app:
Get IOS app bundle id: osascript -e ‘id of app “<.app path>”’

#How to get udid of iOS And Android:
instruments -s devices
adb devices

# Run these command to execute test
For Android
mvn test -DplatformName="Android" -Dudid="ID" -DdeviceName="Google Pixel 3a" -DsystemPort="10000" -DchromeDriverPort="11000"
For IOS:
mvn test -DplatformName="iOS" -Dudid="ID" -DdeviceName="iPhone 11" -DwdaLocalPort="10002" -DwebkitDebugProxyPort="11003"
