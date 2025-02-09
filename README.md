
### **Izhikevich Neuron Model: Simulation and Analysis**

#### **1. Introduction and Starting Point**

The goal of this project is to explore and modify the **Izhikevich neuron model**, a computationally efficient yet biologically accurate model for spiking neurons. This work is based on the **Single Neuron Izhikevich** notebook provided in the course, but with additional elements to extend its scope.

The Izhikevich model is governed by the following differential equations:

with a spike-reset condition:

where represents the membrane potential, is the recovery variable, is the input current, and are parameters defining neuron dynamics.

----------

#### **2. Objectives and Modifications**

The project extends the base Izhikevich model by incorporating **different input currents, neuron types, and parameter explorations**. The key modifications are:

 **Exploring Different Input Currents**:

-   Step current
    
-   Sinusoidal input
    
-   Noisy input
    

 **Simulating Different Neuron Types**:

-   Regular Spiking (RS)
    
-   Fast Spiking (FS)
    
-   Chattering (CH)
    

 **Parameter Exploration**:

-   Effect of varying and parameters on neuron behavior.
    

 **Advanced Analysis**:

-   **Phase Plane Analysis**: Visualizing neuron dynamics in the plane.
    
-   **Firing Rate vs. Input Current (F-I Curve)**: Analyzing how the neuron’s firing rate changes with increasing input.
    
-   **Interspike Interval (ISI) Distribution**: Examining the timing variability of spikes for different neuron types.
    

----------

#### **3. Results and Outcomes**

1. **Neuron Responses to Different Inputs**  
Each neuron type was simulated under step, sinusoidal, and noisy currents. It shows the membrane potential response for a Regular Spiking neuron under different inputs. The results confirm that step currents induce sustained firing, while sinusoidal and noisy currents create more complex firing patterns.

2. **Phase Plane Analysis**  
The phase plane plots illustrate the trajectory of and , showing how neurons stabilize after spiking. Different neuron types exhibit distinct phase trajectories.

3. **Firing Rate vs. Input Current (F-I Curve)**  
The firing rate increases with higher input currents, exhibiting an approximately linear trend. This validates the neuron’s ability to encode stimulus intensity.

4. **Interspike Interval (ISI) Distribution**  
ISI histograms demonstrate that **Fast Spiking neurons** exhibit shorter and more regular ISIs, while **Chattering neurons** have more variability. This aligns with biological neuron behavior.

----------

#### **4. Conclusion and Future Work**

This project extended the Izhikevich neuron model by **adding new input conditions, analyzing different neuron types, and performing advanced analyses**. 

For future improvements, this model could be expanded by:

-   Implementing **synaptic connections** to simulate small neural networks.
    
-   Exploring **stochastic effects** in neuron behavior.
    
-   Comparing results with **biological data** to validate the model.
    