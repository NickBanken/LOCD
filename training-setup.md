# Training setup

For LOCD to run properly, you will need to make the following change on every server and client machine. 

1. Install Kolibri
2. Run Kolibri. It will generate a `.kolibri/options.ini` file.
3. Add the following set of options at the end of the options.ini file:
````
[HTML5] 
SANDBOX = allow-scripts allow-same-origin allow-forms allow-modals allow-popups

````

This needs to be done on every machine (trainer and learner).


