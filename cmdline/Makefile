download:
	wget "https://sourceforge.net/projects/plantuml/files/plantuml.jar/download" -O plantuml.jar

install: download
	mv -vf plantuml.jar /usr/local/bin/
	mv -vf plantumlme.sh /usr/local/bin/
	echo "add execution bit on programms"
	for i in plantuml.jar plantumlme.sh ; do chmod a+x /usr/local/bin/$i ; done
	
