### docker entrypoint  can use at time of   container creation it is acts  as cmd but few changes

1. docker entry point we can't override but cmd we can overide

2. docker cmd command can use to override the  container

3. docker entry-point  we mentioned any default value it give the result 

4. if  you can override . to do so it will go append the entry-point it give the error

5. both commands  can use to contianer creation


CMD ["google.com]

entrypoint["ping","-c5"]

entrypoint ["ping","-c5","yahoo.com;"]