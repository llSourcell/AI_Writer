Overview
============
This code will generate a story based on an image that you input. More information can be found in the [original repo](https://github.com/ryankiros/neural-storyteller). This the code for 'Build an AI Writer' on [Youtube](https://youtu.be/x24VEUEph0Q)

<img src="https://github.com/ryankiros/neural-storyteller/blob/master/images/ex1.jpg" height="220px" align="left">

*We were barely able to catch the breeze at the beach , and it felt as if someone stepped out of my mind . She was in love with him for the first time in months , so she had no intention of escaping . The sun had risen from the ocean , making her feel more alive than normal . She 's beautiful , but the truth is that I do n't know what to do . The sun was just starting to fade away , leaving people scattered around the Atlantic Ocean . I d seen the men in his life , who guided me at the beach once more.*

[Samim](http://samim.io/) has made an awesome blog post with lots of results [here](https://medium.com/@samim/generating-stories-about-images-d163ba41e4ed).


Dependencies
============

* Python 2.7 - (https://www.python.org/downloads/)
* Theano - instructions [here](http://deeplearning.net/software/theano/install.html)
* lasagne - instructions [here](http://lasagne.readthedocs.io/en/latest/user/installation.html)
* scipy `pip install scipy `
* numpy `pip install numpy`

For running on your CPU, you will need to install Caffe and its python interface.

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies

Basic Usage
===========

Simply create a new python file in this repo or run this code from the python command line
```shell
import generate
z = generate.load_all()
generate.story(z, './images/ex1.jpg')
```

Sample output: 
```shell
I let the woman in her eyes , and I had no idea what to say to her . It was a small group of people , both of them . As soon as the taxi arrived , he gave me a hug . It was the first time I 'd spent so much time in New York . In fact , it was almost as if he were going to be the only man in his life , and he made a mental note to pin her down on either side of her body . She loved those men , a little less than ten minutes and I am stunned by someone . - See more at: http://www.somatic.io/examples/4wDNbDm0#sthash.TvSDmyRU.dpuf
```

Credits
===========
Credit for the vast majority of code here goes to [Ryan Kiros](https://github.com/ryankiros). I've merely created a wrapper around some of the important functions to get people started.
