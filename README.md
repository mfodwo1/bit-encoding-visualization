# bit-encoding-visualization
This project is a simple graphical application that visualizes two common bit encoding schemes: NRZ-I and NRZ-L. It allows the user to enter a series of bits and displays the corresponding digital signal for both encoding schemes.

## Features

- Enter a series of bits in the input text field.
- Click the "Encode" button to display the digital sinal for NRZ-I and NRZ-L encodings.
- The digital sinals are displayed in a graphical window, with the x-axis representing time and the y-axis representing the encoded signal level.
- NRZ-I encoding is displayed in blue, and NRZ-L encoding is displayed in red.
- The graphical window is updated each time the "Encode" button is clicked with the new input.

## Getting Started

To run the application, follow these steps:

1. Ensure you have Java Development Kit (JDK) installed on your system.
2. Download or clone the project source code from the repository.
3. Open a terminal or command prompt and navigate to the project directory.
4. Compile the source code by running the following command:
   ``
   javac bitencoding/newpkg/WaveformGUI.java
   ``
5. Run the application using the following command:
   ``
   java bitencoding.newpkg.WaveformGUI
   ``
6. The application window will appear, ready to accept input.

## Usage

1. Enter a series of bits (0s and 1s) in the input text field.
2. Click the "Encode" button to generate the digital sinal for NRZ-I and NRZ-L encodings based on the entered bits.
3. The digital sinal will be displayed in the graphical window, with NRZ-I encoding shown in blue and NRZ-L encoding shown in red.
4. Each time the "Encode" button is clicked, the waveforms will be updated based on the newly entered bits.

## Screenshot


## License

This project is licensed under the [MIT License](LICENSE).
