Project 6 by Tiancheng Gong(tgong7)

Settings and Results:
Network:       		Learning Rate:	NumEpoch:	Layers:			Error Rate:
Shallow Network		0.0001		50		See Code(Comment)	0.461
Deep Network1		0.001		200		See Code		0.542
Deep Network2		0.001		200		Modification*		0.612

Modification:
1. 1st conv layer with 10 (12*12) filters, stride 1
2. 1st maxpooling layer with 10 (6*6) filters, stride 2
3. 2nd conv layer with 10 (6*6) filters, stride 1
4. 2nd maxpooling layer with 10 (3*3) filters, stride 2
5. 3rd conv layer with 10 (3*3) filters, stride 1
6. 3rd maxpooling layer with 10 (2*2) filters, stride 2
7. fc layer with 14 (3*3) filters, stride 1
							   