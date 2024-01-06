# chat-app--using-php
This application is developed by php and mysql

Getting started using the PHAR
Start by downloading our latest PHAR file and giving it a nice and cozy place on your hard drive.

wget https://phpdoc.org/phpDocumentor.phar
After you downloaded the PHAR file, don't forget to power it up by making it executable.

chmod +x phpDocumentor.phar
Also, you may want to consider renaming it to phpdoc; we'll understand.
Then, all you need to do is run it!

Getting started using Docker
Use our very own Docker image; no installation needed!

Treat our docker image like you treat all your other utility images. Just don't forgot to volume mount your current directory to /data inside the container. Remember: No data, No docs.

docker run --rm -v ${PWD}:/data phpdoc/phpdoc:3
Tada!

<h1>Chat Application</h1>
<p>The application sample image is given below...</p>
