
# Vertex Sampler (MCMC)

## Installation
```
clean: make clean
compile: make
```


Please convert the input file into intended format: 
Format:

```
vertex_id_1 vertex_id_2  vertex_1_label edge_label vertex_2_label
```


For using our code, vertex label has to start from 1 and end at the maximum vertex id. 

A converter (python file) is provided under undir_data directory. 

## Sample Output

```
Data File:      undir_data/ca-AstroPhUND.txt-mcmc-format
noofIteration:  2000
sizeOfSubgrah:  100
File reading time: 0.52763 sec
277,937,1316,1372,1407,1614,1952,2030,2266,2286,2305,2329,2393,2456,2569,2676,3074,3136,3386,3667,3912,3968,4413,4669,4699,5092,5110,5599,5668,5827,5856,5952,6114,6161,6634,7071,7453,7529,7559,7567,7572,7802,7830,8930,9283,9311,9342,9548,9647,9908,10212,10272,10381,10465,10484,10705,11352,11650,11658,11688,11733,11849,12256,12753,12868,12942,13342,13396,13668,13884,14037,14080,14120,14303,14323,14573,14752,14859,15047,15161,15405,15629,15728,15990,16088,16317,16916,17029,17085,17281,17302,17436,17439,17510,17599,18123,18219,18458,18464,18562
277,961,1372,1482,1718,1952,2030,2266,2286,2305,2393,2843,3032,3057,3136,3149,3667,3968,4436,4669,4699,4744,4802,5110,5599,5952,6114,6161,6634,6911,7071,7090,7453,7529,7553,7559,7567,7572,7575,7802,7830,8924,8930,8978,9283,9423,9548,9908,10212,10272,10352,10381,10705,10832,10857,11033,11035,11352,11650,11658,11688,11733,11849,12256,12639,12753,12868,12942,13342,13396,13884,13911,14037,14080,14303,14573,14752,14830,14941,15161,15728,15894,15990,16242,16317,16585,16879,17029,17075,17085,17249,17281,17599,17814,18094,18163,18219,18458,18464,18562
```


## Reference
If you are using the code for research purposes, please consider citing any of the following papers:

```
@article{saha.hasan:15,
  title={FS3: A sampling based method for top-k frequent subgraph mining},
  author={Saha, Tanay Kumar and Al Hasan, Mohammad},
  journal={Statistical Analysis and Data Mining: The ASA Data Science Journal},
  volume={8},
  number={4},
  pages={245--261},
  year={2015},
  publisher={Wiley Online Library}
}

@inproceedings{saha.hasan:15*2,
  title={Finding Network Motifs Using MCMC Sampling.},
  author={Saha, Tanay Kumar and Al Hasan, Mohammad},
  booktitle={CompleNet},
  pages={13--24},
  year={2015}
}
```
