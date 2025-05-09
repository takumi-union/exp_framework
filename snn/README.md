# Spiking Neural Network

- Neural network that mimics neuron activation and information propagation.
- "Neuron" takes in some input, accumulates over a period of time, activates if current information level is over a threshold (activation = spike value of 1.0). If level is under threshold, neuron is not activated and spike value is 0.0.
- Network is useful when time period consideration is necessary.

## model_struct.py

Implementation of neurons, layers, and SNN.

## snn_controller.py

Instantiates a robot SNN Controller.

## ring_buffer.py

Implementation of a RingBuffer for keeping track of neuron duty cycles.

