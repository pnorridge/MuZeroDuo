# MuzeroDuo

Based on the pseudocode from 'Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model' (arXiv:1911.08265v2) with added comments to (hopefully) make an easy introduction/tutorial for newcomers.

This version uses two copies of the value function with different discount factors. Also uses the last two game states as the 'image', in an attempt to smooth out noise, etc.

Also, added espilon to the action selection algorithm. LunarLander needs good searching of states, esp late in the training, and the base MuZero algorithm doesn't seem to do this sufficiently.