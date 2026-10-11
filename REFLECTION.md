hw two
flex direction row tells the computer to put things next to each other, while column tells the computer to stack each div on top of each other.
it is important to use relative units and not set pixel as it allows the design to automatically change sizes according to the screen, and fits it nicely. if we were to use set pixels, the size of our object can vary greatly depending on how big our screen is, and we would have to hard code how big we want our text and such to be per device. if we were to use relative units, it solves this problem.

hw one
"Describe the path an HTTP Request takes from a browser to your GitHub Pages site"

it turns the url of the github page to an IP address using DNS
it then uses tcp port 80 (http) which creates a web conection from the device to a server
this request reaches github's server which holds the static files of your github page 
it looks up the current html based on the url that was given 
sends back the html and css back to the client if it was able to successfully retrieve the data
