Common hack to allow a single input to upload multiple files for phpbb Gallery mod
This is ugly, but it works :<
You may need to adapt the normal workflow the way it has been done if u want to use it elsewhere; the same way it has been implemented on gallery/upload.php@upload_file. 
It basically splits the treatement between a normal file or an array of files