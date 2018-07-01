# ImageConv
Image convolution

I have used a 3x3 convolver. For this I have made a fifo (first in first out) in vhdl. As the pixel stream passes through the fifo , 
the pixels are extracted through the 9 pipes and then multiplied with the kernel values.
