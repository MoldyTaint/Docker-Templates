This will be the guide/how to for help setting up this docker compose/stack

In this compose file, we have a few things at play here. We have a main "DOCKER COMPOSE" file which links back to the "ARR APP" "COMPOSE FILE". The reason why I did it like this is to help trouble shoot, add, and delete apps from the stack as you see fit.

In order to have this stack work proporly, there needs to be a set file structure. This is needed for how docker compose, and the apps pull and use things. (Hopefuly that's the write wording)

This is how the directory should be set up. 

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

At this step, we should have created a folder called "Media" somewhere on our ZPool, Harddisk, or wherever you would want these to live/stay.

