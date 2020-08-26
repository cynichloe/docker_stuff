# use remote interpreter in a docker from pycharm

# steps:
1. `docker build -t remoteint .`
2. `docker run -it remoteint`
3. start pycharm:
- add interpreter
![image info](./pics/pic1.png)
- choose a `docker` type interpreter 
![image info](./pics/pic2.png)
- enter the correct python executable path in the container. if not sure, try run the container interactively with `bash` and do `which python`
![image info](./pics/pic3.png)
- voila!
![image info](./pics/pic4.png)
