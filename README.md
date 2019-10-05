# What is it ?
An elm quickstart based on https://elmprogramming.com/

# Why it exists ?
This repository is a template. It was only designed to be fork or clone for other elm projects. For me or for others.

# What's in it ?
It's already contains a setup for elm-live, elm-test, and travis.

# What i need ?
I preferred to use npm with a global setup. So you should do the following commands if you want like me to avoid having to aministrate a node_module the following commands: 
npm install -g elm@0.19.0
npm install -g elm-test@0.19.0-rev3
npm install -g elm-format@0.8.0
npm install -g elm-live

# Npm --local vs --global
If you prefer to use npm with a global setup you should keep in mind that travis may need more configuration.