<b>Voting-ensemble method framework</b><br>
<br>
dependency: <em>jsoup</em> (https://github.com/jhy/jsoup/releases/tag/jsoup-1.6.2)<br>
<br>
<ins>how to run:</ins><br>
java -Xmx1g -cp ./:\<jsoup dir>/jsoup-1.6.2.jar Voting \<threshold> \<source xml dir> \<output dir> \<system<sub>1</sub> dir> \<system<sub>2</sub> dir> ...<br>
<br>
\<jsoup dir>: the directory containing <em>jsoup-1.6.2.jar</em><br>
\<threshold>: voting threshold, e.g., 1, 2<br>
\<source xml dir>: the directory containing XML files with <TEXT> tags (i2b2 2014 deid corpus format)<br>
\<output dir>: an output directory for voting ensemble<br>
\<system<sub>1</sub> dir> ~ \<system<sub>n</sub> dir>: the directories containing the predictions of individual deidenfication systems<br>
<br>
