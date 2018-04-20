Ensemble method framework
voting ensemble

Voting-ensemble method framework

dependency: jsoup (https://github.com/jhy/jsoup/releases/tag/jsoup-1.6.2)

arguments args[0] = voting threshold
args[1] = the directory containing XML files with <TEXT> tags (i2b2 2014 deid corpus format)
args[2] = an output directory
args[3] ~ args[n] = the outputs of individual deidenfication classifiers

how to run

java -Xmx1g -cp ./:<jsoup dir>/jsoup-1.6.2.jar Voting <\threshold> <\target xml dir> <\output dir> <system 1 dir> <system 2 dir> ...

<jsoup dir>: the directory containing jsoup-1.6.2.jar
