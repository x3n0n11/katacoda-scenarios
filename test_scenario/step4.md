This is a prototype for AI chatbot. 

## Chat!

Follow the next few commands to download and save all the files to your computer :)

<pre>Compress the files</pre>
`cd .. `{{execute}}
`tar -czvf chatbot.tar.gz katacoda_chatbot`{{execute}}


`echo "Run in T2"`{{execute T2}}
<pre>`echo "Run in T2"`{{execute T2}}</pre>
Start a webserver for remote access
<!-- ``python2 -m SimpleHTTPServer 8080``  -->
`python3 -m http.server 8000`{{execute}}


`snap install ngrok`{{execute}}
`ngrok http 8000`{{execute}}


<!-- You can now download the file using your web browser https://2886795289-8080-elsy02.environments.katacoda.com/chatbot.tar.gz -->