# Useful Command Line Tools
A collection of useful command line tools and basic usage

## PDFtk - https://www.pdflabs.com/docs/pdftk-man-page/

Installing: sudo apt-get install pdftk 

* Modifying PDF Metadata:
  * pdftk file-name.pdf dump_data output Metadata-output.txt // create text document with meta info
  * vim Metadata-output.txt // modify Metadatt
  * pdftk file-name.pdf update_info Metadata-output.txt output file-name-new.pdf // output changed file

## Postman install script

```
wget https://dl.pstmn.io/download/latest/linux64 -O postman.tar.gz
sudo tar -xzf postman.tar.gz -C /opt
rm postman.tar.gz
sudo ln -s /opt/Postman/Postman /usr/bin/postman
```
