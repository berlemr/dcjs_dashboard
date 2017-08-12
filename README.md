# dcjs_dashboard
sample code for a 1 page dashboard

I find that dc/d3 seems to work best on Chrome.

The d3.csv import functionality will only work if the files are hosted. This can be done locally using python' -mSimpleHTTPServer.
In windows o/s and in the absence of admin rights to set the system path you can do the following:

- in cmd , cd to the local folder with the files to be hosted.
- type in 'set path=<python path>
- test by typing python and verifying that the python shell opens up.
- now you can run python -mSimpleHTTPServer and then in the browser you can put in the local ip and specify port 8000.

Though slightly clunky, the csv import can be replaced by assigning a js object to a variable. In the .html files you can create a variable named data and set = {}

Pretty much all of the .js and .css files in the repo will need to be included to generate a dashboard. The only exception is selecta.js which is used to add a d3 style drop down selection list.
