# common
### step1
        allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	     }
 ### step2
 
      implementation 'com.github.hrxiang:OJBK:1.0'
      
### step3

       android {
           defaultConfig{
                multiDexEnabled true
            }
            ……
           compileOptions {
                sourceCompatibility JavaVersion.VERSION_1_8
                targetCompatibility JavaVersion.VERSION_1_8
           }
            ……
       }