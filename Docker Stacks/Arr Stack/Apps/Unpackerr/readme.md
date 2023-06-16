#### Environment Variables

- **user:** Specify the `USERIDHERE` and `GROUPIDHERE` that Unpackerr should run under.

##### Sonarr Configuration

- **UN_SONARR_0_URL:** Update the URL and port for your Sonarr instance.
- **UN_SONARR_0_API_KEY:** Update with your Sonarr API key.
- **UN_SONARR_0_PATHS_0:** Update with your torrent path in Sonarr.

##### Radarr Configuration

- **UN_RADARR_0_URL:** Update the URL and port for your Radarr instance.
- **UN_RADARR_0_API_KEY:** Update with your Radarr API key.
- **UN_RADARR_0_PATHS_0:** Update with your torrent path in Radarr.

##### Folder Configuration

- **UN_FOLDER_0_PATH:** Specify the path for additional folders, if required.
- **UN_FOLDER_0_EXTRACT_PATH:** Specify the extraction path for folders.
- **UN_FOLDER_0_DELETE_AFTER:** Set the duration after which the folder should be deleted.
- **UN_FOLDER_0_DELETE_ORIGINAL:** Specify whether to delete the original folder.
- **UN_FOLDER_0_DELETE_FILES:** Specify whether to delete files within the folder.
- **UN_FOLDER_0_MOVE_BACK:** Specify whether to move the extracted files back to the original location.

### Security Options

- **no-new-privileges:** Set to `true` to ensure no new privileges are granted to the container.