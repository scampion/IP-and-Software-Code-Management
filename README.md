# Free-and-Open-source-software-licenses
Free and Open-source software licenses


# Author 
Sebastien Campion 
sebastien.campion@pm.me

# License 

Creative Commons BY NC SA

# Tips

convert barn.jpg -gravity center -crop 3:2 +repage barn_crop_3to2.png

convert riccardo-annandale-7e2pe9wjL9M-unsplash2.jpg -fill black -colorize 50% riccardo-annandale-7e2pe9wjL9M-unsplash3.jpg

convertr(){
    convert $1 -resize $3% $2
}

convertb() {
    convert $1 -fill black -colorize $3% $2
}

convertw() {
    convert $1 -fill white -colorize $3% $2
}

convert169() {
    convert $1 -resize x900 -gravity center -background white -extent 1600x900 -quality 85 $2
}

convert169_() {
    convert $1 -resize 1600x -gravity center -background white -extent 1600x900 -quality 85 $2
}