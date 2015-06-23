.PHONY: app platforms cordova-build

app:
	$(MAKE) platforms
	$(MAKE) cordova-build

platforms:
	rm -r platforms/*
	cordova platform add ios &> /dev/null	

cordova-build:
	cordova build
	
