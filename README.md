### Features

Sync to mega foleder every x seconds.

Command needed to use:
docker run --name mega-cmd -e USERNAME="email" -e PASSWORD="password" -e DEST_MEGA_FOLDER=/ -e INT_SECONDS=30 -v path_folder_to_upload:/upload -v ${PWD}/logs:/root/.megaCmd xusmendev/megacmd-sync:1.0.0
