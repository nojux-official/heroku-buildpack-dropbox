# heroku-buildpack-dropbox

## Requirements
  * Dropbox api token

## Environment variables
  * DROPBOX_API_TOKEN (required) - a personal dropbox api token.
  * DROPBOX_FILES_TO_BACKUP (optional) - file names to backup. Format: `<path> [<path> [<path>...]]`
  *  DROPBOX_DESTINATION_PREFIX (optional) - dropbox path to store backups.
  
### Variables for debugging (better to not change):
  * DROPBOX_UPLOADER_SCRIPT_NAME
  * DROPBOX_RESTORE_SCRIPT_NAME
  * DROPBOX_BACKUP_SCRIPT_NAME
  * DROPBOX_STARTUP_SCRIPT_NAME
