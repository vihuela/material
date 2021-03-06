Material
=====================

[![Maven Central](https://img.shields.io/maven-central/v/com.github.rey5137/material.svg)](https://oss.sonatype.org/content/repositories/releases/com/github/rey5137/material/1.1.0/material-1.1.0.aar)  [![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-Material-brightgreen.svg?style=flat)](http://android-arsenal.com/details/1/1685)

MaterialLibrary is an Open Source Android library that back-port Material Design components to pre-Lolipop Android. MaterialLibrary's original author is [Rey Pham](https://github.com/rey5137).

* [Features](#features)
* [Demo](#demo)
* [Getting Started](#getting-started)
* [Donation](#donation)

##Features
- [Progress](https://github.com/rey5137/Material/wiki/Progress)
    - Circular
    
        ![](https://github.com/rey5137/Material/raw/master/image/progress_circular_indeterminate.gif) ![](https://github.com/rey5137/Material/raw/master/image/progress_circular_determinate.gif)
    - Linear

        ![](https://github.com/rey5137/Material/raw/master/image/progress_linear_indeterminate.gif) 
        ![](https://github.com/rey5137/Material/raw/master/image/progress_linear_determinate.gif)
        ![](https://github.com/rey5137/Material/raw/master/image/progress_linear_query.gif)
        ![](https://github.com/rey5137/Material/raw/master/image/progress_linear_buffer.gif)

- [Button](https://github.com/rey5137/Material/wiki/Button)
    
    ![](https://github.com/rey5137/Material/raw/master/image/button_raise_touch.gif) ![](https://github.com/rey5137/Material/raw/master/image/button_raise_wave.gif)

    ![](https://github.com/rey5137/Material/raw/master/image/fab_image.gif) ![](https://github.com/rey5137/Material/raw/master/image/fab_line.gif)   
     
- [Switch](https://github.com/rey5137/Material/wiki/Switch)

    ![](https://github.com/rey5137/Material/raw/master/image/cb.gif)

    ![](https://github.com/rey5137/Material/raw/master/image/rb.gif)

    ![](https://github.com/rey5137/Material/raw/master/image/switch.gif)

- [Slider](https://github.com/rey5137/Material/wiki/Slider)

    ![](https://github.com/rey5137/Material/raw/master/image/slider_continuous.gif)

    ![](https://github.com/rey5137/Material/raw/master/image/slider_discrete.gif)

- [Spinner](https://github.com/rey5137/Material/wiki/Spinner)
     
    ![](https://github.com/rey5137/Material/raw/master/image/spn.gif)

- [Text Field](https://github.com/rey5137/Material/wiki/Text-Field)

    ![](https://github.com/rey5137/Material/raw/master/image/textfield.gif)

- [TabPageIndicator](https://github.com/rey5137/Material/wiki/TabPageIndicator)
     
    ![](https://github.com/rey5137/Material/raw/master/image/tpi.gif)

- [SnackBar](https://github.com/rey5137/Material/wiki/SnackBar)
     
    ![](https://github.com/rey5137/Material/raw/master/image/snackbar.png)

- [Dialog](https://github.com/rey5137/Material/wiki/Dialog)

    ![](https://github.com/rey5137/Material/raw/master/image/dialog_3.png) ![](https://github.com/rey5137/Material/raw/master/image/dialog_4.png)

## Demo

<a href="https://play.google.com/store/apps/details?id=com.rey.material.demo">
  <img alt="Get it on Google Play"
       src="https://developer.android.com/images/brand/en_generic_rgb_wo_60.png" />
</a>

## Getting Started

Add Gradle dependency:

```gradle
dependencies {
   compile 'com.github.rey5137:material:1.1.0'
}
```

* Or
[Download from Maven](https://oss.sonatype.org/content/repositories/releases/com/github/rey5137/material/1.1.0/material-1.1.0.aar)

AppCompat and CardView library is required by Material library.

```gradle
dependencies {
   compile 'com.android.support:appcompat-v7:21.0.2'
   compile 'com.android.support:cardview-v7:21.0.3'
}
```
Now you can use any widget in **com.rey.material.widget** package as you wish. For styling, please view [Wiki](https://github.com/rey5137/Material/wiki).

## Donation
You can support the project and thank the author for his hard work.

<a href='https://pledgie.com/campaigns/28714'><img alt='Click here to lend your support to: Support Material Library project. and make a donation at pledgie.com !' src='https://pledgie.com/campaigns/28714.png?skin_name=chrome' border='0' ></a>

**PayPal**
- [Donate] (https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=pea5137%40gmail%2ecom&lc=US&item_name=Rey%20Pham&no_note=0&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest)

Developed By
------------

* Rey Pham - <pea5137@gmail.com>

Contributing
------------
Want to contribute? You are welcome!

License
--------

    Copyright 2015 Rey Pham.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
