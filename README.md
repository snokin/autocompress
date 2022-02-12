# what is this
- Shell script that auto compress videos under specific folder
- Detect the resolutions of videos and made multiple sized files of compressed videos
# Usage
- copy to /usr/bin  
`autocompress /your/path/to/dir`  
Also you can set it into crontab job to autocompress every videos in a specific folder at the midnight  
`crontab -e  
*/11 1 * * * autocompress /your/path/to/dir`
