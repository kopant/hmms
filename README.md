# hmms
Cheryl Roberts (kopant@gmail.com) <br> <br>

This project includes a class for fitting and decoding HMMs (currently only
discrete emission spaces are supported; extension to GMM is tentatively planned). <br>
The code is tested on a toy example from Wikipedia, as well as real-life example
using gas sensor data. <br>
The jupyter notebook contains the entirety of the code (which should be broken 
out into a proper library in the future), and includes significant exploration
and pre-processing of the MOX gas sensor data. 

## Environment <br>
Code tested with: <br>
+ Python 3.5.2 <br>
+ numpy 1.16.4 <br>
+ pandas 0.24.2 <br>
+ matplotlib 2.2.3 <br>
+ hmmlearn 0.2.3  
<br>
## Datasets <br>
1. MOX gas sensor data, UCI, retrieved from https://archive.ics.uci.edu/ml/datasets/Gas+sensors+for+home+activity+monitoring#
2. Wikipedia worked 'chicken' example for Baum Welch, retrieved from https://en.wikipedia.org/wiki/Baum–Welch_algorithm
<br> <br>
## References <br>
1. Rabiner, L. (1990).
A tutorial on hidden markov models and selected apllications in speech recognition. 
In A. Waibel and K.-F. Lee, editors, Readings in Speech Recognition, pages 267-296. Kaufmann, San Mateo, CA.
2. Russell, S. and Norvig, P. (2009). Artificial Intelligence: A Modern Approach (3rd Edition). Pearson: London, UK. 
3. Gutierrez-Osuna, R. (n.d.) Introduction to Speech Processing, L14: Refinements for HMMs. Retrieved from http://research.cs.tamu.edu/prism/lectures/sp/l14.pdf
