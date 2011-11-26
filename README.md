# jhc

## USAGE

    Usage: jhc -t HTML_TITLE -j jquery,underscore -c bootstrap -e url -r
    Description:
            -t: specify HTML title
            -j: specify javascript libraries
            -c: specify css
            -e: specify url to extract body
            -r: reload wedata config and exit
    Available JavaScript Libraries:
            face_detector   http://lab.gkbr.me/facedetect/facedetector.min.js
            tiny_segmenter  http://chasen.org/~taku/software/TinySegmenter/tiny_segmenter-0.1.js
            backbone        http://documentcloud.github.com/backbone/backbone.js
            underscore      http://documentcloud.github.com/underscore/underscore.js
            jquery  http://code.jquery.com/jquery-1.7.js
    Available StyleSheets:
            bootstrap       https://raw.github.com/twitter/bootstrap/master/bootstrap.css

Just hit the command:

    $ jhc -t "Test App" -j jquery,underscore -c bootstrap testapp
    # welcome to jhc v0.0.4
    add: testapp/js/jquery.js # http://code.jquery.com/jquery-1.7.js
    add: testapp/js/underscore.js # http://documentcloud.github.com/underscore/underscore.js
    add: testapp/css/bootstrap.css # https://raw.github.com/twitter/bootstrap/master/bootstrap.css
    add: testapp/index.html

And you get:

    $ tree testapp
    testapp
    ├── css
    │   └── bootstrap.css
    ├── index.html
    └── js
        ├── jquery.js
        └── underscore.js
    
    2 directories, 4 files

## INSTALL
    gem install jhc

## SEE ALSO

 * <http://d.hatena.ne.jp/hitode909/20110614/1308032945>
