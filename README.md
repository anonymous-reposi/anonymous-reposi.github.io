## MaskPlace: Fast Chip Placement via Reinforced  Visual Representation Learning

A new chip placement method based on visual representation learning.

### The placement process animation

Benchmark: Bigblue3


|Placement| Pos Mask t | Wire Mask t |
|---|---|---|
|<img src="imgs/place.gif" width="250">|<img src="imgs/pos_img.gif" width="250">|<img src="imgs/net_img.gif" width="250">|
|<center><b> View Mask </b></center>| <center><b> Pos Mask t+1 </b></center>| <center><b> Wire Mask t+1 </b></center>|
|<img src="imgs/view_img.gif" width=250>|<img src="imgs/pos_img_next.gif" width=250> | <img src="imgs/net_img_next.gif" width=250>|


### Full Benchmark demonstration


|Benchmark| DREAMPlace | Graph | DeepPR | MaskPlace |
|---|---|---|---|---|
|adaptec1|<img src="imgs/dreamplace/adaptec1.png" width="160">|<img src="imgs/graph/adaptec1.png" width="160">|<img src="imgs/deeppr/adaptec1.png" width="160">|<img src="imgs/maskplace/adaptec1.png" width="160">|
|HPWL (10<sup>5</sup>)|17.94|26.05|21.36|<strong>6.57</strong>|
|Wirel (10<sup>5</sup>)|19.24|28.54|25.64|<strong>7.36</strong>|
|adaptec2|<img src="imgs/dreamplace/adaptec2.png" width="160">|<img src="imgs/graph/adaptec2.png" width="160"> | <img src="imgs/deeppr/adaptec2.png" width="160">|<img src="imgs/maskplace/adaptec2.png" width="160">|
|HPWL (10<sup>5</sup>)|135.32|359.35|197.13|<strong>79.98</strong>|
|Wirel (10<sup>5</sup>)|140.91|381.64|205.78|<strong>83.59</strong>|
|adaptec3|<img src="imgs/dreamplace/adaptec3.png" width="160">|<img src="imgs/graph/adaptec3.png" width="160"> | <img src="imgs/deeppr/adaptec3.png" width="160">|<img src="imgs/maskplace/adaptec3.png" width="160">|
|HPWL (10<sup>5</sup>)|112.28|392.66|340.29|<strong>79.33</strong>|
|Wirel (10<sup>5</sup>)|119.23|409.37|372.02|<strong>85.28</strong>|
|adaptec4|<img src="imgs/dreamplace/adaptec4.png" width="160">|<img src="imgs/graph/adaptec4.png" width="160"> | <img src="imgs/deeppr/adaptec4.png" width="160">|<img src="imgs/maskplace/adaptec4.png" width="160">|
|HPWL (10<sup>5</sup>)|<strong>37.77</strong>|152.89|243.12|75.75|
|Wirel (10<sup>5</sup>)|<strong>47.90</strong>|179.43|290.14|88.87|
|bigblue1|<img src="imgs/dreamplace/bigblue1.png" width="160">|<img src="imgs/graph/bigblue1.png" width="160"> | <img src="imgs/deeppr/bigblue1.png" width="160">|<img src="imgs/maskplace/bigblue1.png" width="160">|
|HPWL (10<sup>5</sup>)|2.50|8.32|20.49|<strong>2.42</strong>|
|Wirel (10<sup>5</sup>)|3.41|10.00|25.68|<strong>3.14</strong>|
|bigblue3|<img src="imgs/dreamplace/bigblue3.png" width="160">|<img src="imgs/graph/bigblue3.png" width="160"> | <img src="imgs/deeppr/bigblue3.png" width="160">|<img src="imgs/maskplace/bigblue3.png" width="160">|
|HPWL (10<sup>5</sup>)|104.05|345.49|439.09|<strong>82.61</strong>|
|Wirel (10<sup>5</sup>)|107.58|373.33|517.86|<strong>88.51</strong>|
|ariane|<img src="imgs/dreamplace/ariane.png" width="160">|<img src="imgs/graph/ariane.png" width="160"> | <img src="imgs/deeppr/ariane.png" width="160">|<img src="imgs/maskplace/ariane.png" width="160">|
|HPWL (10<sup>5</sup>)|20.30|16.83|51.43|<strong>14.86</strong>|
|Wirel (10<sup>5</sup>)|21.72|18.48|55.85|<strong>15.80</strong>|
