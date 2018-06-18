
Repo for group Tensorflow Gerrmany on www.meetup.com/tensorflowgermany


## Step-by-Step Instructions for setting up env for using the notebooks 

__Note__: I will add only instructions for setting up Docker on MacOS so anyone with other exprience can edit this file

### Mac OS

1. Open the Terminal application ([like this](http://www.wikihow.com/Open-a-Terminal-Window-in-Mac))
2. Navigate to desired folder where you want to store the files 
3. Retrieve all of the code for this LiveLessons by executing `git clone https://github.com/djovanoski/tensorflow_germany.git` (if you haven't used `git` before, you may be prompted to install Xcode -- do it!)
4. [Install the Docker "Stable channel"](https://docs.docker.com/docker-for-mac/install/) (if you are already using an older version of Docker and run into installation issues downstream, try updating to the latest version of Docker)
5. Start Docker, e.g., by using Finder to navigate to your Applications folder and double-clicking on the Docker icon
6. Move into the *tensorflow_germany* directory by executing `cd tensorflow_germany`
7. Build the Docker container by executing `docker-compose build` ( this will take a while everything to be dowlonaded and installed)
8. Run the Docker Container by executing `docker-compose up`
9. You are all setup just open your browser and type `localhost:8888` for opening Jupyter Notebook 
10. For opening Tensorboard navigate to new tab in the browser and type `localhost:6006`
11. If you want to use python from the terminal , please open new tab in the terminal or new terminal window and you will need first to find the id of the container so type `docker ps -a` and you will see the id of the tensorflow container copy that and type `docker exec -it <here_paste_the_id> /bin/bash` and you can use python from terminal 


### Windows 
__Will be updated__ ( any interested can help here :) ) 











