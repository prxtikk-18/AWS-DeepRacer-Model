# AWS-DeepRacer-Model
Reinforcement Learning Model using the AWS DeepRacer Console
Training & Evaluation

## Configuration of Model
1. **Sensor** - Camera ( Single-lens 120-degree field of view camera capturing at 15fps. The images are converted into greyscale before being fed to the neural network )
1. **Neural network topology** - 3 Layer CNN
1. **Action space type** - Continuous
1. **Action space** - <pre>Speed: [ 0.5 : 1 ] m/s <br /> 
                           Steering angle: [ -30 : 30 ] °</pre>      
1. **Framework** - Tensorflow
1. **Reinforcement learning algorithm** - PPO




