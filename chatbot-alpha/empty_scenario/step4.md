## Save our progress

<pre>Congratulations once again for creating your own chatbot! There is one step left, which is optional. If you want to save the chatbot you created, along with all other files needed to run it, follow along by clicking the black text boxes. </pre>

<pre>Compress the files</pre>

`cd .. `{{execute}}

`tar -czvf chatbot.tar.gz katacoda_chatbot`{{execute}}

<pre>Use this command to open another terminal (we'll need it in just a little bit)</pre>

`echo "Run in T2"`{{execute T2}}
<pre>`echo "Run in T2"`{{execute T2}}</pre>

<pre>You can switch between the terminals by clicking on either of the tabs, as shown in the picture. </pre>

<pre>
![Terminals ](../assets/terminals.png)
</pre>

![Terminals ](../assets/terminals.png)

<pre>In one terminal you can run this command...</pre>

`python3 -m http.server 8000`{{execute}}

<pre>And then switch to the other terminal and execute the following commands</pre>

`snap install ngrok`{{execute}}
`ngrok http 8000`{{execute}}

<pre>After you are done, click on the link shown, and download chatbot.tar.gz file from there. If you are stuck, here's an image to help you find the link :)</pre>

<pre>
![Address ](../assets/ip_pen.png)
</pre>

![Address ](../assets/ip_pen.png)

