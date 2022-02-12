# what is this
- Auto compress videos under specific folder
- Detect the resolutions of videos and made multiple size files of compressed videos
# Usage
- copy to /usr/bin  
`autocompress /your/path/to/dir`
Also you can set it into crontab job to autocompress every videos in a specofic folder at the midnight  
`crontab -e 
*/11 1 * * * autocompress /your/path/to/dir`
