### ENTRYPOINT
ENTRYPOINT is also used to run the container just like CMD, but there are few differences 
1. We can't override in ENTRYPOINT like in CMD 
2. CMD acts as argument provider to ENTRYPOINT when we use both commands 