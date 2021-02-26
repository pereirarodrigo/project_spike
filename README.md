# spike
Spiking neural networks are one of the more interesting ideas born from neuroscience. A model that mimics natural neural networks more closely than traditional artificial neural networks, spiking neural networks are a rather radical departure from the aforementioned neural models and are heavily reliant on differential equations and other concepts, such as time, to be employed. They're prevalent in neuromorphic engineering, and, as of now, can only be run efficiently in simulations. Still, their impact on artificial intelligence is undeniable, as this kind of network is slowly being adapted to tasks that traditional neural networks took care of so far and, slowly but surely, is being improved upon and is starting to catch up to even the most advanced models in deep learning.

This project's goal is to study the leaky integrate-and-fire model, simulate a spiking neural network and apply it to machine learning and reinforcement learning tasks through the use of BindsNET, a Python package that uses PyTorch's Tensor functionality to simulate such a network. It's available here: https://github.com/BindsNET/bindsnet. Additionally, OpenAI Gym is used for reinforcement learning algorithms and environments - you can also grab it here: https://github.com/openai/gym.

Main references used in this project are:

* "BindsNET User Manual", at BindsNET's Read the Docs page. Available at: https://bindsnet-docs.readthedocs.io/guide.html;
* "Neuronal Dynamics", by Wulfram Gerstner et al. (2014) at Neuronal Dynamics' web page. Available at: https://neuronaldynamics.epfl.ch/online/index.html;
* "Spike-timing dependent plasticity", at Scholarpedia. Available at: http://www.scholarpedia.org/article/Spike-timing_dependent_plasticity
* "Deep Learning in Spiking Neural Networks" by Amirhossein Tavanaei et al. (2019), at ArXiv. Avaiable at: https://arxiv.org/pdf/1804.08150.pdf.




