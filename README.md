# GadIssues

### Formatting github readme 3 ###
                 
                 https://github.com/tchapi/markdown-cheatsheet/blob/master/README.md
                 
### Retrofit not working on android < android 5 3 ###
 
                     fixed with these dependecies 
                             implementation 'com.google.code.gson:gson:2.6.2'
                             implementation 'com.squareup.retrofit2:retrofit:2.5.0'
                             implementation 'com.squareup.retrofit2:converter-gson:2.0.2'
  
### Entry name 'AndroidManifest.xml' collided (Build failed after updating the android gradle plugin to 3.6.0) 3 ###

                    - try add android.useNewApkCreator=false in gradle.properties
                    - delete release apk and regenerate it 
                    
### You need to use a Theme.AppCompat theme (or descendant) with this activity 3 ###
                
                https://stackoverflow.com/a/40184937/7698605
                
### Locale not changing in signed apk 3 ###
               
               https://stackoverflow.com/a/53442299/7698605
                
                    
 
