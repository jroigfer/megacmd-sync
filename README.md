### Features

Sync to mega foleder every x seconds.

Command needed to use:
docker run --name mega-cmd -e USERNAME='email' -e PASSWORD='password' -e TARGET=$DEST_MEGA_FOLDER \
-v 'path_folder_to_upload':/upload -v ${PWD}/logs:/root/.megaCmd jroigfer/megacmd-sync:latest