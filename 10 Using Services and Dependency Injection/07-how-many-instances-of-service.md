# How Many Instances of Service Should It Be?
01. If you want to use the same instance of a service from a parent component, don't add it to providers
02. Still import it and add it to the constructor
03. Sometimes you may want to use a new instance, but make sure you're using the one you want