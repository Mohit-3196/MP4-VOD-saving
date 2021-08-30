# MP4-VOD-saving
To save only highest quality or a specific bitrate in the MP4 recording when ABR is enabled.
The script enables saving only specific bitrate MP4 VOD recording when ABR is enabled in ant media server. 
It can be used with S3 recordinds as well.
## AMS Side Process
We need to add settings.muxerFinishScript=/home/ubuntu/scripts/user_defined.sh parameter in /usr/local/antmedia/webapps/{Application-Name}/WEB-INF/red5-web.properties.
Here is [User-Defined scripts](https://github.com/ant-media/Ant-Media-Server/wiki/User-defined-Scripts)
###### Please be sure your script is in right path and enable MP4 recording in Application settings.
