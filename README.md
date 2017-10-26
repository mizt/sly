## sly   
Tokisato Miztsuru 2015 - 

======================
### requirements
Mac OS X 10.9+

### usage

    mkdir ~/Pictures/sly
    cp settings.json ~/Pictures/sly
    
    cp ~/Desktop/hoge.jpg ~/Pictures/sly
    cp ~/Desktop/hoge.png ~/Pictures/sly
    cp ~/Desktop/hoge.gif ~/Pictures/sly
    cp ~/Desktop/hoge.pdf ~/Pictures/sly
    cp ~/Desktop/hoge.svg ~/Pictures/sly
    
    open /Applications/sly.app
    
### key bindings

| key | action |
| :-: | --- |
| esc | fullscreen mode on \ off |
| right | load next image |
| left | load prev image |
| space | auto mode on \ off |
| 1 - 9 | specifies the amount to stops in auto mode |
| r | load random image |
| b | background mode cover \ contain |
| g | transforms an image to grey scale |
| c | hide \ unhide cursor |
| t | hide \ unhide text |
| up | load next directory |
| down | load prev directory |
| f | directory freeze on \ off |

### setting.json

| key | value |
| --- | --- |
| root | / |
| auto  | true |
| speed | 5 |
| background.color | '#000' |
| background.mode | 'cover' |
| title.font | 'Hiragino Kaku Gothic ProN' |
| title.size | '64px' |
| title.height | '1.2em' |
| title.weight | 'bold' |
| title.color | '#FFF' |
| title.x | (WINDOW_W-TEXT_W)>>1|
| title.y | (WINDOW_H-TEXT_H)>>1|
| title.content | FILE_NAME.slice(0,FILE_NAME.length-4) |
| title.exclusion | false |
| title.visible | false |
| fullscreen | false |
| cursor | true |

\* unit of text.x / y is 'px';


