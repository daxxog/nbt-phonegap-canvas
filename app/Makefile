.PHONY: app platforms cordova-build

app:
	if [ ! -d bower_components ] ; \
	then \
		$(MAKE) bower ; \
	fi;
	if [ ! -d platforms ] ; \
	then \
		$(MAKE) platforms ; \
	fi;
	$(MAKE) cordova-build

bower:
	bower install

platforms:
	rm -r platforms/*
	cordova platform add ios	

cordova-build:
	cordova build
	
