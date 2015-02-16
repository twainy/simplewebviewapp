Simple Webview App
===
Simple Webview App is a very simple application. That has only webview.

Setting
---
Please edit AndroidManifest.xml

```AndroidManifest.xml
    <application android:label="@string/app_name" android:icon="@drawable/ic_launcher">
        <activity android:name="MyActivity"
                  android:label="@string/app_name">
            <intent-filter>
                <action android:name="android.intent.action.MAIN"/>
                <category android:name="android.intent.category.LAUNCHER"/>
            </intent-filter>
        </activity>
-        <meta-data android:name="webview_url" android:value="http://www.google.co.jp"/>
+        <meta-data android:name="webview_url" android:value="http://yourwebsite.example.com"/>
    </application>
```
