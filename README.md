# Game Closure DevKit Plugin: AppsFlyer

This plugin adds install tracking support from the [AppsFlyer service](http://www.appsflyer.com) for Android.

## Usage

Install the addon with `basil install appsflyer`.

Include it in the `manifest.json` file under the "addons" section for your game:

~~~
"addons": [
	"appsflyer"
],
~~~

Under the Android section, you can configure the plugin:

~~~
	"android": {
		"versionCode": 1,
		"appsFlyerKey": "pLNhfW1gijisAwKg64s6hC"
	},
~~~

Note that the key names are case-sensitive.

You can test for successful integration on the [AppsFlyer website](http://www.appsflyer.com).

