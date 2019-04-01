RockOS 
========
## Downloading Source
To initialize your local repository, use this command:

	repo init -u https://github.com/rock-os/manifest.git -b 9.0

Then to sync, use this command:

	repo sync -c -j8 --force-sync --no-clone-bundle --no-tags
	
		
## Building RockOS
After download RockOS source now you able to build rom by type 
``` . 
  build/envsetup.sh
  lunch rock_CODENAME-userdebug 
  ``` 
Then to start build 
```
  mka rock 
```

## Credits
- [GZOSP](http://GitHub.com/gzosp) 
- [LineageOS](http://GitHub.com/LineageOS) 
- [BaikalOS](http://GitHub.com/BaikalOS) 
- [AospExtended](http://GitHub.com/AospExtended)
