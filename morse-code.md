<div align="centre">
<h1> morse-code </h1>
</div>

### Information:

Morse code is well known. Can you decrypt this? Download the file <a href ="https://artifacts.picoctf.net/c/235/morse_chal.wav">here. </a>
Wrap your answer with picoCTF{}, put underscores in place of pauses, and use all lowercase.

### Hint:
Audacity is a really good program to analyze morse code audio.

### Solution:
We have to write down the dot and the dashes from the file <a href ="https://artifacts.picoctf.net/c/235/morse_chal.wav">morse_chal.wav.</a>

``` sh
.-- .... ....- --... / .... ....- --... .... / ----. ----- -.. / .-- ..--- ----- ..- ----. .... --...
```
By analysing it using the   <a href= "https://modernout.com/pages/morse-code-chart">morsce code table.</a>
```sh
wh47 h47h 90d w20u9h7
```
The final flag is 
```sh

picoCTF{wh47_h47h_90d_w20u9h7}
```

