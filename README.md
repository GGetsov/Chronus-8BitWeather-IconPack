# 8bit Weather Icon Pack for Chronus

This project utilizes the [DvTonder/Sample_icon_set](https://github.com/DvTonder/Sample_icon_set) template for creating Chronus icon sets and is heavily inspired by [thepolovinkin's](https://stock.adobe.com/bg/contributor/205400330/thepolovinkin) [weather icon set](https://stock.adobe.com/images/weather-symbols-web-icons-pixel-art-set-contains-such-icon-as-rain-clouds-drizzle-wind-snow-night-thunderstorm-and-sun-design-for-mobile-app-sticker-logo-isolated-vector-illustration/359824760).    

## Installation

1) CD into the directory
2) Use `gradlew build` to build the project. Keep in mind you mind need to set the value for the ANDROID_SDK_ROOT env variable. 
3) Find the apk files (debug and release) inside the app\build\outputs\apk directory
4) Copy to device and install.

## Customization

The project not only provides the files needed for building the apk, but also the aseprite files for anyone wishing to modify the icons. All moon phases are displayed via the same icon. Chronus icon sets use the original Yahoo weather codes. If you wish to make any changes to the weather and moon icons use the proper filename for each icon (`weather_{$code}` or `moon_{$code}` to match the desired weather descriptions or moon phases). Changing the app_name string in values.xml and the ic_launcher.png image will change the app name and icon respectivly. For more info on customization head to the [DvTonder's project](https://github.com/DvTonder/Sample_icon_set).

### Original Yahoo weather codes:

| Code 	| Description                    	|
|------	|--------------------------------	|
| 0    	| tornado                        	|
| 1    	| tropical storm                 	|
| 2    	| hurricane                      	|
| 3    	| severe thunderstorms           	|
| 4    	| thunderstorms                  	|
| 5    	| mixed rain and snow            	|
| 6    	| mixed rain and sleet           	|
| 7    	| mixed snow and sleet           	|
| 8    	| freezing drizzle               	|
| 9    	| drizzle                        	|
| 10   	| freezing rain                  	|
| 11   	| showers                        	|
| 12   	| rain                           	|
| 13   	| snow flurries                  	|
| 14   	| light snow showers             	|
| 15   	| blowing snow                   	|
| 16   	| snow                           	|
| 17   	| hail                           	|
| 18   	| sleet                          	|
| 19   	| dust                           	|
| 20   	| foggy                          	|
| 21   	| haze                           	|
| 22   	| smoky                          	|
| 23   	| blustery                       	|
| 24   	| windy                          	|
| 25   	| cold                           	|
| 26   	| cloudy                         	|
| 27   	| mostly cloudy (night)          	|
| 28   	| mostly cloudy (day)            	|
| 29   	| partly cloudy (night)          	|
| 30   	| partly cloudy (day)            	|
| 31   	| clear (night)                  	|
| 32   	| sunny                          	|
| 33   	| fair (night)                   	|
| 34   	| fair (day)                     	|
| 35   	| mixed rain and hail            	|
| 36   	| hot                            	|
| 37   	| isolated thunderstorms (day)   	|
| 38   	| scattered thunderstorms (day)  	|
| 39   	| scattered thunderstorms (day)  	|
| 40   	| scattered showers (day)        	|
| 41   	| heavy snow                     	|
| 42   	| scattered snow showers (day)      |
| 43   	| blizzard                       	|
| 44   	| partly cloudy (night)          	|
| 45   	| scattered showers (night)         |
| 46   	| scattered snow showers (night)    |
| 47   	| scattered thundershowers (night)  |
| na   	| data not available             	|

### Moon Phase codes:

- Moon phase images are named moon_xx.png (or use the WebP format for smaller files)
- You need at least 8 drawables at 0, 15, 25, 35, 50, 65, 75, 85 and 100. Max is 100 drawables
- Customize its moon.xml in the drawable folder to match the drawables you created

## Licensing

This project is licensed under the [GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.html), but i don't recommend creating a consumer product using it due to the heavy use of/ inspiration by material that is not owned me. Thanks again to the contributors of the [Sample_icon_set project](https://github.com/DvTonder/Sample_icon_set) and [thepolovinkin](https://stock.adobe.com/bg/contributor/205400330/thepolovinkin) for all the great work!
