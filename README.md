# update_checker


## How To Install

```
repositories {
        maven {
            url "https://raw.github.com/oxtonAccount/update_checker/main"
        }
....
}
```


Then add:

```
implementation 'com.oxtondigital.update:updateapp:release_version'
```


Code:

```
String APP_UPDATE_SERVER_URL = "https://url/update.json";
UpdateChecker.checkForDialog(getActivity(), APP_UPDATE_SERVER_URL, true, true);
```