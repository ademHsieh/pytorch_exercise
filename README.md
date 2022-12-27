# pytorch
## calculate new img size
W = original img size  <br>
ex. img size = 128 * 128 , original img size = 128 <br>
ks = kernal size <br>
ex. kernal size = 5x5x5 , ks = 5  <br>
S = strid step<br>
pad = padding step<br><hr>

<p><b><h3> new img size = ((W + 2*pad - ks) / S ) + 1 <h3><b><p>

