# experiments

Experiments with machine learning.

Bad Habits is a simple experiment on how we can create our own interventions using machine learning to manage our bad habits. When you're mindlessly carrying out habitual actions in front of the laptop, GIFs will appear to tell you to stop when you're doing something bad and encourage you when you're doing something healthy.
This project uses Processing and ml4a.

How it works

Using the Convnet Classifier from ml4a, the machine is trained to recognise 3 states - (1) drinking a cup of water, (2) pulling out your hair, and (3) normal where nothing is happening. These states are classified and sent to Processing where they will trigger the corresponding GIFs to be played - telling you to stop or encouraging you to do more of certain actions.
