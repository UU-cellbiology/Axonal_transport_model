# Axonal_transport_model

Simple mathematical model of bidirectional active transport in axons (written in Mathematica).

General assuptions are:  
1) axonal microtubules are unidirectional (plus ends to periphery/growth cone)  
2) there are different ratios of kinesins/dyneins per single cargo  
   
It corresponds to equations described in the publication:  
LF Gumy, EA Katrukha, LC Kapitein, CC Hoogenraad <a href="http://onlinelibrary.wiley.com/doi/10.1002/dneu.22121/full">New insights into mRNA trafficking in axons</a> Developmental neurobiology, 2014   

It consists of two files, first is to find how average probability density function (PDF) changes over time:  
<b>part1_average_PDF.nb</b>   
<img src="http://katpyxa.info/software/Axonal_transport_model/part1_ill.gif">    

The second part simulates stochastic individual cargo movements:   
<b>part2_stochastic_MonteCarlo.nb</b>  
<img src="http://katpyxa.info/software/Axonal_transport_model/part2_stochastic_MonteCarlo.png">  
   
     
<img src="http://katpyxa.info/software/Axonal_transport_model/multiple_partice_diffusion.gif">


Developed in <a href='http://cellbiology.science.uu.nl/'>Cell Biology group</a> of Utrecht University.  
E-mail <a href="mailto:katpyxa@gmail.com">for any questions</a>.
