# Flash-Chat
A simple message app to demostrate using firebase, cocoapods, tableViews, and other basic UIDesign. This app was completed on Udemy.com/londonbreweryapp

# Features:

- Register user
- Login user
- Send messages

#Cocoapods used in this lesson 
- SVPProgressHUB 
- ChameleonFramework 
- Firebase

#Update podfile erros with these instruction 
## Podfile Configuration
```
post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
        end
    end
end
```




This project was completed for personal ios development skills and all rights belong to - Copyright © The App Brewery
