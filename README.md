sly
======================
###requirements
Mac OS X 10.9+

###usage

    mkdir ~/Pictures/sly
    cp settings.json ~/Pictures/sly
    
    cp ~/Desktop/hoge.jpg ~/Pictures/sly
    cp ~/Desktop/hoge.png ~/Pictures/sly
    cp ~/Desktop/hoge.gif ~/Pictures/sly
    
    open /Applications/sly.app
    
###key bindings

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
| t | hide \ unhide filename |

###setting.json

| key | value |
| --- | --- |
| text.font | 'Hiragino Kaku Gothic ProN' |
| text.size | 64px |
| text.weight | bold |
| text.color | #FFF |
| text.x | (WINDOW_W-TEXT_W)>>1 |
| text.y | (WINDOW_H-TEXT_H)>>1  |
| text.content | FILE_NAME.slice(0,FILE_NAME.length-4) |


