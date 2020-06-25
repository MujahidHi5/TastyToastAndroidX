# TastyToast

Make your native android toast look beautiful.

## Preview
![gif](https://github.com/yadav-rahul/TastyToast/blob/lib/static/success.gif)
![gif](https://github.com/yadav-rahul/TastyToast/blob/lib/static/warning.gif)
![gif](https://github.com/yadav-rahul/TastyToast/blob/lib/static/error.gif)
![gif](https://github.com/yadav-rahul/TastyToast/blob/lib/static/info.gif)
![gif](https://github.com/yadav-rahul/TastyToast/blob/lib/static/default.gif)
![gif](https://github.com/yadav-rahul/TastyToast/blob/lib/static/confusion.gif)

## About

Refer Here [Wiki](https://github.com/yadav-rahul/TastyToast/wiki)


## Dependency

Add dependency in your app module

```
dependencies {
		implementation 'com.github.immujahidkhan:TastyToastAndroidX:0.0.1'
}
```

## Usage

### Java
```
TastyToast.makeText(getApplicationContext(), "Hello World !", TastyToast.LENGTH_LONG, TastyToast.WARNING);
```
Last parameter here is the type of toast you want to show.
