This repository holds the source code for my the presentation of my
[Neural NILM paper](http://jack-kelly.com/files/writing/neural_nilm.pdf)
for EPRI in November 2016.

If you just want to view this presentation, just point your browser to
[jackkelly.github.io/EPRI_NeuralNILM](http://jackkelly.github.io/EPRI_NeuralNILM);
you do not have to clone this repository just to view the presentation.

---

If you do want to clone the repository then you'll need to install
these packages:

```
sudo apt-get install nodejs-legacy npm
sudo npm install -g grunt-cli http-server bower
bower install
```

Then run `http-server -c-1` from the base directory of this project.
And point your browser to `http://localhost:8080`.
