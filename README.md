# jhc

## USAGE
    $ jhc -j jquery -s bootstrap testapp
    
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
        <title></title>
                      <script language="javascript" type="text/javascript" src="./javascripts/jquery.js"></script>
                                <link rel="stylesheet" type="text/css" href="./stylesheets/bootstrap.css" />
                </head>
      <body>
      </body>
    </html>

## INSTALL
    gem install jhc
