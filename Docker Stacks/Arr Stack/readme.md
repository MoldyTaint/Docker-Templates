## Welcome to the Docker Compose Stack Setup Guide

This guide aims to provide you with step-by-step instructions on how to set up and configure a Docker Compose stack. Whether you're a beginner or have limited experience with GitHub and Docker, this guide will help you navigate through the process smoothly.

### Understanding the Compose Files

Within this stack, we have two essential files: the main `DOCKER COMPOSE` file and the associated `ARR APP` `COMPOSE FILE`. This clever design allows for seamless troubleshooting, easy app additions, and painless removals from the stack as per your requirements.

### File Structure Requirements

To ensure the stack functions flawlessly, it is crucial to maintain a specific file structure. This structure facilitates Docker Compose and the apps within the stack to effortlessly pull and utilize the required resources. By adhering to this standardized file structure, you can optimize the performance and stability of your Docker Compose stack.

Feel free to delve deeper into the instructions and explore specific configurations. Should you need any further assistance, don't hesitate to ask. Happy Docker Compose stacking!


This is how the directory should be set up. 

```
/Pathtoprefereddirectory
 -> Media
    -> Management
        -> docker-compose.yaml
        -> Apps
            -> Deemix
                -> docker-compose.yaml
                -> Configs
            -> Prowlarr
                -> docker-compose.yaml
                -> Configs
            -> Radarr
                -> docker-compose.yaml
                -> Configs
            -> Sonarr
                -> docker-compose.yaml
                -> Configs
            -> Unpackerr    
                -> docker-compose.yaml
                -> Configs
```
At this step, we should have created a folder called "Media" somewhere on our ZPool, Harddisk, or wherever you would want these to live/stay.

