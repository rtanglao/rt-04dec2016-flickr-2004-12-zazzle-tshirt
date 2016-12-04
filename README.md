# rt-04dec2016-flickr-2004-12-zazzle-tshirt
flickr 2004-2012 zazzle tshirt

## December 4, 2016

* 1. copy the average hex colour file from
  https://github.com/rtanglao/rt-animated-gifs/blob/master/2016-11-03/flickr-roland-2004-12-avgcolour.txt
  to here: ```cp ../rt-animated-gifs/2016-11-03/flickr-roland-2004-12-avgcolour.txt .```
* 2. ```mv flickr-roland-2004-12-avgcolour.txt flickr-roland-2004-12-avgcolour.csv``` and add line 1 with "colour"
* 3. ```Rscript zazzle-tshirt-flickr2004-12-square-pie-chart.R flickr-roland-2004-12-avgcolour.csv ```
