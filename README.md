# blender-2.7-startup-file-improved
Improved startup file for Blender 3D 2.79b

## What's changed in this file (compared to default Blender)

### 3D Viewport changes

* Default Render Engine is Cycles Render:

![change-topbar](https://user-images.githubusercontent.com/391735/54474075-40ccef00-481b-11e9-9383-865e7c231c02.png)

* No default cube
* Grid lines to 100

![view](https://user-images.githubusercontent.com/391735/54474435-b470fb00-481f-11e9-95e2-9a3d93323eaf.png)

* 3D Viewport camera clip is from 10cm to 1km
* Default 3D Cursor location is 1m high (so that, when you create new object, it is on the ground):

![change-view-3d-cursor](https://user-images.githubusercontent.com/391735/54474124-de282300-481b-11e9-9185-3a3379517b27.png)

### Render Changes

* Resolution to 100%
* Frame Rate to 60 fps

![render-dimensions](https://user-images.githubusercontent.com/391735/54474272-0ca6fd80-481e-11e9-8622-6f21b80dcdab.png)

* If you're developing game, I suggest to turn off Reflective Caustics and Refractive Caustics (greatly improves render times), but it is not turned off by default (good for photorealistic rendering)

![render-light-paths](https://user-images.githubusercontent.com/391735/54474273-0ca6fd80-481e-11e9-9b21-1e21e66659a6.png)

* Tiles size changed to 512x512 (good for GPU), if you use CPU Render, change to small value (e.g. 64x64)

![render-performance](https://user-images.githubusercontent.com/391735/54474274-0d3f9400-481e-11e9-8ec2-e21e91424c4c.png)

* GPU Render by default

![render-render](https://user-images.githubusercontent.com/391735/54474275-0d3f9400-481e-11e9-886b-0ce770b5c22e.png)

* 512 samples for renders, 8 samples for preview

![render-sampling](https://user-images.githubusercontent.com/391735/54474276-0d3f9400-481e-11e9-9800-7e2b3a8ef180.png)

## Suggested User Preferences

### Interface:

* Do not display Python Tooltips
* Do not Show Splash

![user-prefs-interface](https://user-images.githubusercontent.com/391735/54473821-f5fda800-4817-11e9-840b-ab47e6097a02.png)

### Editing:

* Set Undo Steps to 64

![user-prefs-editing](https://user-images.githubusercontent.com/391735/54474000-3d853380-481a-11e9-92d9-f01cf6ae5d16.png)

### Input:

* Select With Left mouse button
* Emulate Numpad

![user-prefs-input](https://user-images.githubusercontent.com/391735/54474002-437b1480-481a-11e9-98cb-d536eee73003.png)

### System:

* Enable GPU Rendering (CUDA) (you will need to install CUDA)

![user-prefs-system](https://user-images.githubusercontent.com/391735/54474006-4c6be600-481a-11e9-91fd-6e4c859d8833.png)

## Recommended Addons:

![user-prefs-addons](https://user-images.githubusercontent.com/391735/54474008-51309a00-481a-11e9-9fe5-10669604e41f.png)
