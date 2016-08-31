# SunDatePicker
Date picker for Iranian calendar 

[![](https://jitpack.io/v/zaaferani67/SunDatePicker.svg)](https://jitpack.io/#zaaferani67/SunDatePicker)

## Screenshots

<img src="/Preview.jpg" width="400" height="400"/>


## Getting started

To get a Git project into your build:


####Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:


```
allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```

####Step 2. Add the dependency

```
dependencies {
        compile 'com.github.zaaferani67:SunDatePicker:v1.0.0'
}
```

### Usage

```java
 new DatePicker.Builder()
            .id(id)
            .theme(theme)
            .date(initialDate)
            .build(MainActivity.this)
            .show(getSupportFragmentManager(), "");
```

# Licence

    Copyright 2016 Alireza Afkar
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
