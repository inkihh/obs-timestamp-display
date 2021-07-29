# Permanently visible, dynamic OBS timestamp

For documentation reasons, you may want to display a dynamic timestamp in your OBS video permanently. I haven't found a vanilla way to do this, so here's this.

* Save timestamp.html somewhere on your local drive
* Create a new Browser source in OBS
* As URL, paste the path to that file, C:\Users\inkihh\Documents\Github\obs-timestamp-display\timestamp.html in my case
* Set Width to 200 and Height to 25. You can alter these values later, if they don't fit your environment
* Drag it into a corner
* Done!

To change the background and/or text color, just edit this bit locally:

![GitHub Logo](/images/1.jpg)

For these changes to take effect while OBS is running, you'll have to restart obs, or change something in the Browser source settings window.
