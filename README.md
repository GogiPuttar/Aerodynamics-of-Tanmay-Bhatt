# Aerodynamics-of-Tanmay-Bhatt
Inspired by a meme termed "Aerodynamics of Tanmay Bhatt", I decided to undertake the task of actually finding the aerodynamics of the comedian named Tanmay Bhatt.

To do this I would have to obtain a 3-D model of Tanmay Bhatt's body and then run an ANSYS simulation of the 3-D model in a wind tunnel. Since people don't usually have #-D models of themselves uploaded on the internet and making a 3-D model of a person, is way too big of an ask for me so I set out to find an alternative. Facebook's PIFuHD AI was created to make 3-D models of people just by looking at a 2D image of them. I followed their link on GitHub, ran the code on Colab and supplied it with smaple images until I got something usable.

You could try this too with the following links:
* GitHub with full documentation: https://github.com/facebookresearch/pifuhd
* Colab Demo: https://colab.research.google.com/drive/11z58bl3meSzo6kFqkahMa35G5jmh2Wgt?usp=sharing
* Video Tutorial: https://youtu.be/QANxO69y6r4

In my experience, a full body photo of a person with the background removed gives the best results. Finally, I used the sculpting feature in Blender to make correct any imperfections.

I tried running a simulation on ANSYS however the model is too detailed so the software keeps crashing ¯\_(ツ)_/¯

