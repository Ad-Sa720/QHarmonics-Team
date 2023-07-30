# QHarmonics-Team

# 1.Quantum Piano Sonata Generator

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Description

The Quantum Piano Sonata Generator is a Python-based software that uses quantum circuits to generate piano sonatas. This project explores the fascinating intersection of quantum computing and music composition, providing a unique and creative way to generate original piano music.

## Features

- Generate Piano Sonatas: The software utilizes quantum-inspired random generation to create novel and unpredictable piano sonatas. The generated sonatas have both regularity and randomness, creating a unique musical experience with each run.

- Quantum Circuit-Based Generation: The project includes quantum circuits designed using the qiskit library. Hadamard gates are applied to each qubit, and the measurement results produce a sequence of 4-bit binary numbers, which determine the note offsets.

- Piano Range and Harmonic Progressions: The generated sonatas cover the entire piano range, from A0 to C8, ensuring that the compositions explore the full spectrum of musical notes. Harmonic progressions are incorporated to create musically coherent pieces.

- MIDI Conversion and Playback: The project uses music21 and pygame libraries to map the generated MIDI note numbers to corresponding piano notes. The sonatas can be played back and saved in MIDI or WAV format.

## How to Use

1. Install the required dependencies:

pip install qiskit music21 pygame

2. Run the `generate_sonata.py` script: python generate_sonata.py

3. The software will create a quantum circuit and simulate it to generate the piano sonata. The result will be displayed as a list of MIDI note numbers representing the generated sonata.

4. To play the generated piano sonata, the script will automatically convert the MIDI notes into playable music using pygame.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Credits

This project was inspired by the concept of quantum music generation and is based on the ideas presented in the paper 

## Contribution

Contributions to the project are welcome! If you find any issues or want to add new features, feel free to submit a pull request.

Happy music generation with quantum circuits!



