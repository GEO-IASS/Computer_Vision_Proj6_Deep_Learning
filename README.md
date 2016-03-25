# Computer_Vision_Proj6_Deep_Learning
Project 6 by Tiancheng Gong(tgong7)

Settings and Results:

|Network        |Learning Rate|NumEpoch|Layers		    |Error Rate|
|:--------------|:------------|:-------|:-------------|---------:|
|Shallow Network|0.0001       |50		   |See Code      |	    0.461|
|Deep Network1	|0.001		    |200		 |See Code	    |     0.542|
|Deep Network2  |0.001		    |200		 |Modification*	|   	0.612|

Modification:<br/>
1. 1st conv layer with 10 (12\*12) filters, stride 1<br/>
2. 1st maxpooling layer with 10 (6\*6) filters, stride 2<br/>
3. 2nd conv layer with 10 (6\*6) filters, stride 1<br/>
4. 2nd maxpooling layer with 10 (3\*3) filters, stride 2<br/>
5. 3rd conv layer with 10 (3\*3) filters, stride 1<br/>
6. 3rd maxpooling layer with 10 (2\*2) filters, stride 2<br/>
7. fc layer with 14 (3\*3) filters, stride 1
 
See more details at: [Computer Vision Project 6 Website](http://all4win.github.io/projects/cv_proj6/index.html)
