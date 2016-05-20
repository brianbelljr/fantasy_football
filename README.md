# fantasy_football
Data Science for Fantasy Football


####Docker image with environment:
`docker pull brianbelljr/fantasy-football`

https://hub.docker.com/r/brianbelljr/fantasy-football/


#Steps:
###1. Pull the container
`docker pull brianbelljr/fantasy-football`
###2. Run container and expose the correct ports
`docker run -it -p 8888:8888 brianbelljr/fantasy-football /bin/bash`
###3. Inside the container, run Jupyter notebook at the correct IP address:
`ipython notebook --ip=0.0.0.0 --no-browser`
###4. Leave that running, now find the Jupyter server with your host-system browser:
Navigate to [http://localhost:8888/](http://localhost:8888/)
