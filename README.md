OCR with Neural Nets
====================

this project is for computing practice & theory at the evergreen state college.

the end goal of this project is to implement optical character recognition for
handwritten characters and to give the unicode equivalents using neural networks.
the current goal of this project is to implement optical character recognition
for computer generated images of text with some fonts.

**dependancies**: python2.7 or python3 with some small modification

in order to run, download the repo and navigate to the downloaded folder in the command line.

there you can change the inputs to the neural network in the *params* subfolder. I named
my params file params.dat, so I run my neural net by typing the following in the command line

```
python main.py params.dat
```

Components:
============
* main
  * main
  * hasKey
  * indent
  * dStruct
* neuralNet
  * neuron
  * neuralNetLayer
  * neuralNet
* propagate
  * backprop
  * sigmoid
  * derivSigmoid
  * errorGradientOutputLayer
  * errorGradientHiddenLayer
  * derivActivation
  * activation
  * y
  * deltaThreshhold
  * deltaWeight
  * sum
  * randLst
* preprocess
  * receptor
* fileLib
  * getDataFromFile
* imagePreProcessing
  * PIL
  * todo:
     * need to merge

the following sources are the inspiration for the code
i've written and the resources that i used to understand
the fundamentals of my implementation.

Sources:
--------
   - http://www.codeproject.com/Articles/11285/Neural-Network-OCR
   - http://www.ibm.com/developerworks/library/l-neural/
   - http://home.agh.edu.pl/~vlsi/AI/backp_t_en/backprop.html
   - http://www.ai-junkie.com/ann/evolved/nnt1.html
   - http://www.engineering.upm.ro/master-ie/sacpi/mat_did/info068/docum/Neural%20Networks%20for%20Pattern%20Recognition.pdf
   - http://itee.uq.edu.au/~cogs2010/cmc/chapters/BackProp/

