# ML2 Project X - A text2image2text (T2I2T) Pipeline
Hello and welcome to my project for the exam in the ML2 module.

It's a small project combining Natural Language Processing and Computer Vision.

The goal is to create a pipeline where you can enter an initial caption. The Stable Diffusion Model is then used to generate an image based on this caption. In the final step, the BLIP model is employed to generate a caption from the resulting image. Subsequently, a word embedding is used to compare the similarity between the initial and generated captions.

A few important tips:
* Make sure to **start with the first notebook** '01_text2image2text_pipeline.ipynb'!
* You need quite **a lot of GPU power** to run the notebooks. So make sure you have an available GPU.
* When using Google Colab (like I did), you might **consider to upgrade to Pro** so you can use an A100 GPU. Other Runtimes (including the free ones) should work as well, but I can not guarantee for anything. Also it might take an even longer time to run the notebooks. 

Now you are ready to dive in. Enjoy!