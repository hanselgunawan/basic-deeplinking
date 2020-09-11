# Basic Deeplinking

## Implementation
### Add `intent-filter` to AndroidManifest.xml
```
<intent-filter>
    <action android:name="android.intent.action.VIEW"/>
    <category android:name="android.intent.category.BROWSABLE"/>
    <category android:name="android.intent.category.DEFAULT"/>
    <data
        android:scheme="http"
        android:host="www.example.com"/>
</intent-filter>
```
### Open this link
```
http://www.example.com
```

## App Demo
<img src="https://i.gyazo.com/775139c7390fe644391a3e8daebc8f12.gif" width="350px" height="650px" />
