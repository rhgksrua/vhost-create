## Apache VirtualHost Manager

### Creates, show, and remove Apache virtual hosts.


#### List of arguments


##### create

````
makevhost create servername documentroot [filename]
````

servername and documentroot is required.
filename defaults to servername.

The script will add a file to ````/etc/apache2/sites-available/```` and enable it.

##### remove

```
makevhost remove filename
```

filename must exist in ````/etc/apache2/sites-available/```` directory.

filename will be disabled and removed completely.

##### show

````
makevhost show
````

Displays all files currently in ```/etc/apache2/sites-enabled/``` directory.
