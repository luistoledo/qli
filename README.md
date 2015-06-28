# qli
terminal quicklook for the internetz

a script adding URL support to osx's quicklook launcher [qlmanager]

prepared to be used inside your own scripts/stuff

## features
- download file from url into a temp directory
- if file already exist, doesn't download it again
- shows a cursor spinner while downloading [1]
- display downloadings errors, and exits with error code 1

## usage
``qli https://upload.wikimedia.org/wikipedia/commons/7/78/Cat_fall_150x300_6fps.gif`

## system wide installation
- copy qli script into your local bin folder: ``cp qli /usr/local/bin/``
- give execution permisions: ``chmod +x qli``

[1]: http://fitnr.com/showing-a-bash-spinner.html