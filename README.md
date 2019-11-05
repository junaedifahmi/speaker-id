# Speaker Identification Using PyTorch



## Data
The data used in this experiments is from Voxceleb Dataset. Among all the speaker present, I chose 100 speaker randomly, and take their voices within 5 minutes duration each. Then, the data is processed with turning them to MFCC coefficients.

## Method

The raw data, then we extract using MFCC method with 40 dimensions coefficients. After that, we just throw it in the neural network. The training scheme is just like another training scheme. We made an iteration with 100 epo


## Result


![Image description](https://www.kaggleusercontent.com/kf/9105487/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..zt66WqWodgHeJeWTjzKR0g.Br4FBvR5hM-9bGkj_MMsd0j94n2l72HA-VLwrob6rkecQPymswg-Y6btrEUa7zbAX2JRLdM1XVakLuoYWfwJUZMN6bGN5bw3RgfZlSZzvKJDjYsFq1lsACePJkybZmMe-70JBBfKb2LAsEHRxHUNITsG5M3VQJNqkyGbtTV65NY.8H7Uv0NP3inv3DtV18fflQ/__results___files/__results___8_0.png)
