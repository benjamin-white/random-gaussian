# **_Random Gaussian_**

This repo is a placeholder. The previous code for creating a Gaussian / normal distribution has been lost but I believe broadly followed the SO discussion [here](https://stackoverflow.com/questions/25582882/), provisioning a custom implementation of the below methods. With a new Gaussian object it would be nice to control the fall-off and have an option to set clipping on the output range.

### **_TODO: Test, benchmark and (potentially) add implementations for the following methods. Prefer npm libs where available._**

+ Box-Muller transform
+ [Central limit theorem](https://en.wikipedia.org/wiki/Central_limit_theorem)
+ [Marsaglia polar method](https://en.wikipedia.org/wiki/Marsaglia_polar_method) [[random-normal package](https://github.com/mock-end/random-normal)]
+ [Ziggurat](https://www.npmjs.com/package/node-ziggurat)
+ Ratio-of-uniforms

Useful references:
+ https://github.com/errcw/gaussian
+ https://github.com/processing/p5.js/blob/v1.5.0/src/math/random.js#L151
