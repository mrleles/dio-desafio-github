Create or check the checksum: 

Openssl sha1 filename.txt 

 

Git maintain the contents in Blobs, with metadata 

The Blobs are kept in Trees, trees have metadata 

 

Create ssh key: 

ssh-keygen -t ed25519 -C user@mail.com 

Put the content of the public key in the Github settings 

Do the following commands: 

eval $(ssh-agent -s) 

ssh-add privatekey 
