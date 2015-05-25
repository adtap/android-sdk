# adtap android sdk

## Beta Support ##

This is first beta for android sdk, please report any bugs seen to support@adtap.com

## Usage ##
Under AndroidManifest.xml please include
```
    <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />

    <application>
        <meta-data android:name="adtap_api_key" android:value="[ADTAP_API_KEY]" />
	</application>
```

In your layout xml, please enter following
```
	<com.adtap.sdk.AdtapView
	    android:layout_width="match_parent"
    	android:layout_height="wrap_content"
    	android:layout_alignParentBottom="true"
	/>
```

If everything is successful, you should see the following

![ScreenShot][1]


## License ##

Copyright 2015 adtap

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

[1]: http://beta.adtap.com/screenshot2.png
