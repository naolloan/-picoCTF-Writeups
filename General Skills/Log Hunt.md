## Challenge Information

> Category: General Skills

> Difficulty: Easy

> Challenge Name: Log Hunt

> Challenge Link: https://play.picoctf.org/practice/challenge/527

##  Problem Statement

> Our server seems to be leaking pieces of a secret flag in its [logs](https://challenge-files.picoctf.net/c_amiable_citadel/49cec6157142f24a599f4164d5b63322c2494f801390d6f22eb91b3aa592bc66/server.log). The parts are scattered and sometimes repeated. Can you reconstruct the original flag? Download the logs and figure out the full flag from the fragments.

## Steps

> First you need to copy the logs from the [link](https://challenge-files.picoctf.net/c_amiable_citadel/49cec6157142f24a599f4164d5b63322c2494f801390d6f22eb91b3aa592bc66/server.log) provided in the problem statement and after that we need to find and organize the flags from the contents of the logs.

> Having copied the link to the logs, we need to go to our shell and organize our logs and proceed to find our flag. You can use your own shell or pico's shell. I will be using Pico's provided shell.

> Now we will download the logs file using wget command. After downloading you can find a server.log file in the home folder.

>    
