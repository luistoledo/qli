# qli
a terminal quicklook for the internetz (and locals)

*qli* add URL support to osx's quicklook launcher [qlmanager]

its prepared to be used inside your own scripts/stuff

## features
- preview local files
- when using url: caches the file into a temp directory(can be overrided)
- display downloadings errors

## usage
`qli https://upload.wikimedia.org/wikipedia/commons/7/78/Cat_fall_150x300_6fps.gif`

`qli mewmew.mp3`

## system wide installation
- copy qli script into your local bin folder: ``cp qli /usr/local/bin/``

or

- link this repo to your local bin folder: ``ln -s fullpath/qli /usr/local/bin/``

and
- give execution permisions: ``chmod u+x qli``

[from_fitnr]: http://fitnr.com/showing-a-bash-spinner.html
