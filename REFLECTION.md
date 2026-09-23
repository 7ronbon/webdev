"Describe the path an HTTP Request takes from a browser to your GitHub Pages site"

it turns the url of the github page to an IP address using DNS
it then uses tcp port 80 (http) which creates a web conection from the device to a server
this request reaches github's server which holds the static files of your github page 
it looks up the current html based on the url that was given 
sends back the html and css back to the client if it was able to successfully retrieve the data
