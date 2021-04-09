# DriveSync (Personal usage only)
This is a fork from  https://github.com/MStadlmeier/drivesync.git

## Customizations
- never delete local files
- no download remote files

## Config
````
bundle install
ruby drivesync.rb config # to edit configuration
ruby drivesync.rb # will print drive url for permissions and start uploading
````

## Usage
- `ruby drivesync.rb` sync all local files into google cloud
- `REUPLOAD_EXT=.mp4 ruby drivesync.rb` re-upload certain files with indicated extensions 
