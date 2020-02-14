All multipliers in this directory are signed multipliers!

The files are named according to the schemata:

	SIZE-STAGE1_STAGE2_STAGE3


SIZE:	Input bit size of the multiplier (16bit means that the design multiplies two 16bit numbers, i.e. 16*16)


STAGE1:	The type of first multiplier stage (partial product generator)
	
	SP: Simple partial product generator
	BP: Booth partial product generator


STAGE2:	The type of second multiplier stage (partial product accumulator)
	
	AR: Array 
	CT: Compressor tree
	DT: Dadda tree
	WT: Wallace tree
	BD: Balanced delay tree
	OS: Overturned-stairs tree


STAGE3:	The type of third multiplier stage (final stage adder)
	
	RC: Ripple carry adder
	BK: Brent-Kung adder
	LF: Lander-Fischer adder
	CL: Carry look-ahead adder
	KS: Kogge-Stone adder
	CK: Carry-skip adder
	CS: Carry select adder
	CU: Conditional sum adder
	BL: Block carry look-ahead adder
	RL: Ripple-block carry look-ahead adder

