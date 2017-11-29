# Compressorone

Aggiungere root build.gradle :

    allprojects {
        repositories {
           maven { url 'https://jitpack.io' }
        }
      }
Aggiungere alle dependency di build.gradle a livello app :

  	dependencies {
	        compile 'com.github.davidevaliante:Compressone:0.1.0'
	  }
