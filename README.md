# Rabbit
Explore Text-To-Speech


## Tacotron
Implementation of [Tacotron: A Fully End-to-End Text-To-Speech Synthesis Model](https://arxiv.org/abs/1703.10135), 

- [x] Griffin-Lim Algorithm
- [ ] Vanilla seq2seq
- [ ] GRU encoder
- [ ] Tacotron
- [ ] Analysis



### Usage
```
pip install -r requirements.txt
```

#### Griffin-Lim Algorithm
D. W. Griffin and J. S. Lim, "Signal estimation from modified short-time Fourier transform," IEEE Trans. ASSP, vol.32, no.2, pp.236–243, Apr. 1984.
        
```
./GriffinLim_example.py sample.wav
```

![GriffinLim](tacotron/sample.png)


