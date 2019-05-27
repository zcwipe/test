# Add it in your root build.gradle at the end of repositories:
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
 # Add the dependency in your model build.gradle
 dependencies {
	        implementation 'com.github.zcwipe:test:1.0.0'
	}
