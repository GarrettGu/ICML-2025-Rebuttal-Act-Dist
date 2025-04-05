In the following set of figures, we visualize the activation distribution for each layer in the VGG-16 architecture. $x_p$ denotes the 99.99th percentile of activations, indicated by the rightmost red dashed line. The encoding range of TTFS, $[\frac{1}{64}x_p, x_p]$, corresponds to the region to the right of the leftmost red dashed line. For CSS, the encoding range is $[\frac{1}{8}x_p, x_p]$, i.e., the region to the right of the middle red dashed line.

We report the relative proportion of activation counts within the two different encoding ranges, along with the average number of spikes used by CSS to encode a single activation. As shown in the figures, **much fewer neurons are activated under CSS coding, and on average, it takes only around 1.5 spikes per activation**.



* ReLU 1:
    <img src="figs/2.png" width=640/>
    
* ReLU 2:
<img src="figs/5.png" width=640/>

* ReLU 3:
    <img src="figs/9.png" width=640/>

* ReLU 4:
    <img src="figs/12.png" width=640/>

* ReLU 5:
    <img src="figs/16.png" width=640/>

* ReLU 6:
    <img src="figs/19.png" width=640/>

* ReLU 7:
    <img src="figs/22.png" width=640/>

* ReLU 8:
    <img src="figs/26.png" width=640/>

* ReLU 9:
    <img src="figs/29.png" width=640/>

* ReLU 10:
    <img src="figs/32.png" width=640/>

* ReLU 11:
    <img src="figs/36.png" width=640/>

* ReLU 12:
    <img src="figs/39.png" width=640/>

* ReLU 13:
    <img src="figs/42.png" width=640/>