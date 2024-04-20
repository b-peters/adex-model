# The adaptive exponential integrate-and-fire model (AdEx)

The given notebook contains my final project in the *Neurodynamics* course at Osnabrück University (Summer Semester 2023).

It explores the capabilities and limitations of the adaptive exponential integrate-and-fire model (AdEx) by Brette & Gerstner (2005).

First, the notebook introduces the mathematical definition of the AdEx model and outlines the significance of the individual model parameters.

The AdEx model enables to display diverse neuronal behaviour. Eight examples of possible firing patterns are examined: 
- tonic spiking
- adaptation
- initial & regular bursting
- delayed acceleration
- delayed regular bursting
- transient spiking
- irregular spiking

These behaviours will be shown by plotting the trajectories of the two variables as well as their dynamics within the phase plane.
Simulations of AdEx model behaviour are implemented using the *Brian2* package in Python.

Furthermore, the Jupyter notebook briefly explains the subthreshold dynamics of the model in terms of the excitability and oscillations of the system depending on parameter choices.

## References

Badel, L., Lefort, S., Brette, R., Petersen, C. C. H., Gerstner, W., & Richardson, M. J. E. (2008). Dynamic I-V Curves Are Reliable Predictors of Naturalistic Pyramidal-Neuron Voltage Traces. *Journal of Neurophysiology*, 99(2), 656–666. https://doi.org/10.1152/jn.01107.2007

Brette, R., & Gerstner, W. (2005). Adaptive Exponential Integrate-and-Fire Model as an Effective Description of Neuronal Activity. *Journal of Neurophysiology*, 94(5), 3637–3642. https://doi.org/10.1152/jn.00686.2005

Clopath, C., Jolivet, R., Rauch, A., Lüscher, H.-R., & Gerstner, W. (2007). Predicting neuronal activity with simple models of the threshold type: Adaptive Exponential Integrate-and-Fire model with two compartments. *Neurocomputing*, 70(10), 1668–1673. https://doi.org/10.1016/j.neucom.2006.10.047

Fourcaud-Trocmé, N., Hansel, D., Vreeswijk, C. van, & Brunel, N. (2003). How Spike Generation Mechanisms Determine the Neuronal Response to Fluctuating Inputs. *Journal of Neuroscience*, 23(37), 11628–11640. https://doi.org/10.1523/JNEUROSCI.23-37-11628.2003

Gerstner, W., & Brette, R. (2009). Adaptive exponential integrate-and-fire model. *Scholarpedia*, 4(6), 8427. https://doi.org/10.4249/scholarpedia.8427

Gerstner, W., Kistler, W. M., Naud, R., & Paninski, L. (2014). Neuronal Dynamics: From Single Neurons to Networks and Models of Cognition. Cambridge University Press. https://doi.org/10.1017/CBO9781107447615

Hill, A. V. (1936). Excitation and accommodation in nerve. *Proceedings of the Royal Society B*, 119:305-355. https://doi.org/10.1098/rspb.1936.0012

Hodgkin, A. L., & Huxley, A. F. (1952). A quantitative description of membrane current and its application to conduction and excitation in nerve. *The Journal of Physiology*, 117(4), 500–544. https://doi.org/10.1113%2Fjphysiol.1952.sp004764

Hunter, J. D. (2007). Matplotlib: A 2D graphics environment. *Computing in science & engineering*, 9(03), 90-95. https://doi.org/10.1109/MCSE.2007.55

Izhikevich, E. M. (2003). Simple model of spiking neurons. *IEEE Transactions on Neural Networks*, 14(6), 1569–1572. https://doi.org/10.1109/TNN.2003.820440

Izhikevich, E. M. (2007). Dynamical Systems in Neuroscience. MIT Press. https://doi.org/10.7551/mitpress/2526.001.0001

Morris, C., & Lecar, H. (1981). Voltage oscillations in the barnacle giant muscle fiber. Biophysical journal, 35(1), 193-213. https://doi.org/10.1016/s0006-3495(81)84782-0

Naud, R., Marcille, N., Clopath, C., & Gerstner, W. (2008). Firing patterns in the adaptive exponential integrate-and-fire model. *Biological Cybernetics*, 99(4), 335–347. https://doi.org/10.1007/s00422-008-0264-7

Stimberg, M., Brette, R., & Goodman, D. F. (2019). Brian 2, an intuitive and efficient neural simulator. *ELife*, 8, e47314. https://doi.org/10.7554/eLife.47314

Touboul, J. (2008). Bifurcation Analysis of a General Class of Nonlinear Integrate-and-Fire Neurons. *SIAM Journal on Applied Mathematics*, 68(4), 1045–1079. https://doi.org/10.1137/070687268

Touboul, J., & Brette, R. (2008). Dynamics and bifurcations of the adaptive exponential integrate-and-fire model. *Biological Cybernetics*, 99(4), 319–334. https://doi.org/10.1007/s00422-008-0267-4
