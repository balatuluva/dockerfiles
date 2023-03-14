### ARG
ARG is used to supply few variables at image creation 
ARG is the only instruction we can use befor FROM 

### use ENV & ARG for best results
create one ENV variable and assign the value of ARG to that
Then we can access ARG values through ENV both in image and container 
