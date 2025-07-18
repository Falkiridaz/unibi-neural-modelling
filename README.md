# Modeling Project

The idea is to implement (and simulate) synaptic transmission and to implement the hodgkin-huxley model to make it more biologically realistic.





# Modeling Synaptic Transmission with the Hodgkin-Huxley Model

The Hodgkin-Huxley Model consists of these four ODEs:


### Current Balance Equation
$ C \frac{dV}{dt} = I_{app} - g_{Na}m^3h(V-E_{Na}) - g_Kn^4(V-E_K) - g_L(V-E_L) $

With...
|Short|Formula|
|---|---|
| $I_{Na_V}$ | $g_{Na}m^3h(V-E_{Na})$ |
| $I_{K_V}$ | $g_Kn^4(V-E_K)$ |
| $I_L$ | $g_L(V-E_L)$ |

### a
$ \frac{dm}{dt} = -\frac{m-m_\infty(V)}{\tau_m(V)} $

### b
$ \frac{dh}{dt} = -\frac{h-h_\infty(V)}{\tau_h(V)} $

### c
$ \frac{dn}{dt} = -\frac{n-n_\infty(V)}{\tau_n(V)} $



> Idan Segev (as quoted in Lindsay (2022)):
>
> "Use Hodgkin-Huxley in an extended way and build a simulation of the way these cells are active, to get the music - the electrical activity - of this network of neurons that should imitate the real biological network that you're trying to understand!

