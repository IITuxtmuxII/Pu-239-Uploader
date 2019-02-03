# Pu-239 Uploader
This can be used to upload a single file or call it from another file and upload multiple torrents.

Point the upload.php script to a single folder and upload 1 torrent or point the loop_example.php script a folder of folders and upload many torrents with the same category.

### If mktorrent is not installed
```
sudo apt-get install mktorrent
```

### Clone the repo
```
git clone https://gitlab.com/darkalchemy/Pu-239-Uploader.git
```

### Install dependancies
```
cd Pu-239-Uploader
composer install
```

### Edit config.php
```
nano config.php
```

### Running on a single folder ```php upload.php``` and follow the prompts

### Running on multiple folders, point ```upload_loop.php``` to the parent folder
```
php upload_loop.php /path/to/parent/folder/
```

### To update
```
git pull
composer install
```
