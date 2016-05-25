<h1>S3Bucket - Create bucket and mount using Fuse/FuseS3</h1>

<h3>How to use:</h3>

This script allows to mount a S3 bucket in Linux Distribuition ( RHEL Based ).<br />
Uses S3Fuse ( https://github.com/s3fs-fuse/s3fs-fuse ) to mount S3 Amazon on system and automatically adds on fstab.

Usage:<br />
      [-i|--install] [-f|--force]<br />
      [-e|--enable] [-r|--remove] USER<br />
      [-ftp|--ftp]<br />
      [-h|--help]<br />
       
      -i      Install the FuseS3 and FuseLib
      -e      Create bucket on server
      -i      Remove bucket from server
      -ftp    Install VSTP ftp server
      -h      Call this help
      -f      Force argument, use only if you need to reinstall all libs

Examples:<br />

<b>sh --install</b>   ( This option will compile S3Fuse in your system )<br />
<b>sh --enable</b>    ( This option mount a bucket for a user on your system )<br />
<b>sh --ftp</b>       ( This option will install and configure VSFTP service to work with this script )<br />

Screens:<br />
<img src="http://i.imgur.com/yPDtfQL.png" />

<br />

<img src="http://i.imgur.com/3tzJUhi.png" />

<br />

<img src="http://i.imgur.com/R35QWtp.png" />

If you have any doubts, please ask.
