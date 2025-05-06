THIS SOFTWARE IS NOT MENT TO BE USED AS WEBSERVER OR PUBLIC NETWORK, LOCAL AND SECURE PRIVATE NETWORKS ONLY.
Read LICENSE.txt

VM - stands for virtual machine

1) HOW DO I CONNECT?

This software creates local server.
When Application run, a command prompt console shows up. There is information about the connection.

You can type:
    
    On PC/Host localhost:5000 OR http://localhost:5000
    On VM:     10.0.2.2:5000 OR http://10.0.2.2:5000

	! NOTE THAT THIS PORT IS ONLY AN EXAMPLE, NOT AN ACTUAL PORT !
	Port 5000 is most likely to open, but if occupied it will be different

Note that this is http not https.

2) What is "resource" and "wwwroot" folder?

wwwroot - is folder containing all static files, that means they are available with links like a directories.
    You can find there uploaded files, database in json files, css, javascript and html.

resource folder is directory with files that are not static and cannot be accessed through the network.
    You can find there files that are used by application and modify when You know what are You doing.

3) Questions
    Q: Do I need to run application both PC/Host and virtual machine?
    A: No, You need to run it only on Host/PC

    Q: Do I need a browser?
    A: No, browser is only for graphical interface, communication is based on REST API

    Q: Where do I find API docs?
    A: localhost:[CURRENT PORT]/api OR in application folder "docs/api.txt"

    Q: How do I shut down application?
    A: Simply close command prompt or press ctrl + c. Connection will close and port will be free

    Q: Can I modify files?
    A: Yes, as long as You do it for private use. Otherwise read LICENSE.txt