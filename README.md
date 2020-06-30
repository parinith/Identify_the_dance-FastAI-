
<p><img src="https://github.com/parinith/Identify_the_dance-FastAI-/blob/master/dance2.PNG" width="800" height="400"></p>

<h4>Problem statement</h4>

This International Dance Day, an event management company organized an evening of Indian classical dance performances to celebrate the rich, eloquent, and elegant art of dance. Post the event, the company planned to create a microsite to promote and raise awareness among the public about these dance forms. However, identifying them from images is a tough nut to crack.

You have been appointed as a Machine Learning Engineer for this project. Build an image tagging Deep Learning model that can help the company classify these images into eight categories of Indian classical dance.

<h4>Dataset</h4>


The dataset consists of 364 images belonging to 8 categories, namely manipuri, bharatanatyam, odissi, kathakali, kathak, sattriya, kuchipudi, and mohiniyattam.

Test data Link : https://drive.google.com/drive/folders/1jTE2rxPMoQ6T2PG27r5T8TO7YJBHYM9W?usp=sharing

Train data link : https://drive.google.com/drive/folders/1kDxzCjIJI2iIbetYRo8IIB9LWzkJ-NWy?usp=sharing

If we have to take the image from directory we have to create driectories in the name of the classes <a href= "https://github.com/parinith/Identify_the_dance-FastAI-/blob/master/createdir.ipynb">notebook1</a>

To insert images into these folders<a href ="https://github.com/parinith/Identify_the_dance-FastAI-/blob/master/imageintofolder.ipynb">notebook2</a>


Detailed Approach for <h3>FastAI</f3> is written in detail in the <a herf='https://github.com/parinith/Identify_the_dance-FastAI-/commit/6ee5e26cfdef4a14b48f42a83b69881141d512a8' >notebook3</a> also contains about diffrent augmentation techniques that are provied in default.

I was able to achive a score of about accuracy 89.9% for the test case.
<p><img src="https://github.com/parinith/Identify_the_dance-FastAI-/blob/master/dance.PNG" width="700" height="300"></p>
