# ML2 Project X - A text2image2text (T2I2T) Pipeline
Hello and welcome to my project for the exam in the ML2 module.

This is a small project combining Natural Language Processing and Computer Vision.

### Motivation
You might have heared of the game GarticPhone (https://garticphone.com/). It's a digitalized, slightly adapted version of a kids game called "telephone game". 
There is no winner or looser, but instead the entertainment comes from comparing the different sentences and images. Obscure situations and funny moments are guaranteed.
My initial goal was to create a machine learning based version of this to generate some entertaining results. 
Sadly, the results weren't exactly funny, because unlike kids (or adults) using paint, the StableDiffusion model is actually really good at generating images. So I had to reevaluate my approach and I decided that I want to find a way to compare the outputs with each other and maybe find a way to improve those results. Which brings me to my new goal.

### Project Goal
The goal is to create a pipeline where you can enter an initial caption. The Stable Diffusion Model is then used to generate an image based on this caption. In the final step, the BLIP model is employed to generate a caption from the resulting image. Subsequently, a word embedding is used to compare the similarity between the initial and the generated captions.
When this is done, the next step is to evaluate how good this performs and what measures can be taken to increase this similarity. Afterwards those measures are tested and compared.

### Running the notebooks yourself
A few important tips:
* Make sure to **start with the first notebook** '01_text2image2text_pipeline.ipynb'! Then just follow the further steps detailled in the Notebooks.
* It is recommended to use Google Colab to run the notebooks.
* You need **a lot of GPU power** to run the notebooks. So make sure you have an available GPU.
* When using Google Colab (like I did), you might **consider upgrading to Pro** so you can use an A100 GPU. Other Runtimes (including the free ones) work as well (as long as you have a connected GPU), but it will take an even longer time to run the notebooks. 

Now you are ready to dive in. Enjoy!
