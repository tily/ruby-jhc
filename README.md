# jhc

## USAGE
    $ jhc 
    Usage: jhc -t HTML_TITLE -j backbone,underscore,jquery -s bootstrap
    $ jhc -t "hello world" -j jquery -s bootstrap testapp
    
    $ ls testapp/*
    testapp/index.html
    
    testapp/javascripts:
    jquery.js
    
    testapp/stylesheets:
    bootstrap.css
    
    $ cat testapp/index.html 
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <title>hello world</title>
                      <script language="javascript" type="text/javascript" src="./javascripts/jquery.js"></script>
                                <link rel="stylesheet" type="text/css" href="./stylesheets/bootstrap.css" />
                </head>
      <body>
      </body>
    </html>

## INSTALL
    gem install jhc

## SEE ALSO

 * <http://d.hatena.ne.jp/hitode909/20110614/1308032945>
