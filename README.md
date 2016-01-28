# PinyinUtils
汉字转拼音 -- for personnal use

Usage:

    allprojects {
  		repositories {
  			...
  			maven { url "https://jitpack.io" }
  		}
  	}
  	
  	dependencies {
          compile 'com.github.Syehunter:PinyinUtils:1.0.0'
  	}
  	
If 'META-INF/maven/com.belerweb/pinyin4j/pom.properties' occurs(maybe in AndroidStudio 2.0), add this to build.gradle


    packagingOptions {
        exclude 'META-INF/maven/com.belerweb/pinyin4j/pom.properties'
        exclude 'META-INF/maven/com.belerweb/pinyin4j/pom.xml'
    }
