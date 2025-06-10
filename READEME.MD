# Overview

This is a music visualizer for Julia. It loads wav files by converting them into MP3, and allows seeing the frequencies change in real time. I wanted to make something in Julia because I know its an up and coming language for data science, as well as being relatively fast compared to other languages. I wanted to do something that tested it's real time processing capabilities, and realized that a music visualizer was a perfect way to test this.

[Here is a video demonstration of the project](https://youtu.be/-i1LnBTx5zY)

# Development Environment

The project uses Julia with several different packages, the biggest one being GLMakie. Other packages used include Statistics, Dates, WAV, DSP, FFTW, GLMakie, GeometryBasics, and Printf

# Useful Websites

Various tutorials for Julia were helpful, but I focused on:
[From zero to Julia!](https://techytok.com/from-zero-to-julia/)
The language came across as pretty similar to python, and did not seem as difficult to use as I was anticipating.

- [OpenCV C++ Install, Build, Run using VS Code and CMake (Debug and Release)](https://youtu.be/CnXUTG9XYGI)
- ChatGPT was very useful for the project, but I did have to understand what the code was doing in order to do this.

# Future Work

I learned a lot about processing frequencies. There are a lot of changes that could be made to improve this project:

- Instead of just mono signal, stereo information could be presented mirrored below but opposite the direction of the other bars.
- An entire revamp, and instead of graphing, using just an empty black plot and attempting to use physics simulations to visualize the music is a long term goal, but the visualizer is a sort of proof of concept.
- A separate window for viewing details could be made instead of using the terminal.