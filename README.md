<h1>S3Bucket - Create bucket and mount using Fuse/FuseS3</h1>

<h3>How to use:</h3>

This script allow you to mount a S3 bucket in Linux Distribuition ( RHEL Based ).
Uses S3Fuse ( https://github.com/s3fs-fuse/s3fs-fuse ) to mount Amazons3 on system and automatically add on fstab.

Usage:
      [-i|--install] [-f|--force]
      [-e|--enable] [-r|--remove] USER
      [-ftp|--ftp]
      [-h|--help]
       
      -i      Install FuseS3 and FuseLib
      -e      Create bucket on server
      -i      Remove bucket from server
      -ftp    Install VSTP ftp server
      -h      Call this help
      -f      Force argument, use with install if you need to reinstall all libs

Examples:

<b>sh --install</b>   ( This option will compile S3Fuse in your system )
<b>sh --enable</b>    ( This option enable a bucket for user on your system )
<b>sh --ftp</b>       ( This option install and configure VSFTP to work with this script )

If hou have any doubts, please ask.
