## ras.sync.client  
1. Create list of files to sync.
2. Push files to raspberry pi stage folder.

## ras.sync.server  
1. Run by cron.
2. Make list of files in stage.
3. Copy all new files to autoscript folder.
4. Move prev versions to backup folder in stage.