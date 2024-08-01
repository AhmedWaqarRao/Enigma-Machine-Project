**Enigma Machine Project**

**Overview**

This project focuses on simulating the Enigma machine, a cipher device developed and used in the early- to mid-20th century for encoding and decoding messages. The Enigma machine was considered highly secure and was used to protect commercial, diplomatic, and military communication. The project involved implementing an Enigma machine simulator using C++.

**Project Requirements**

- **Project Name:** Enigma Machine
- **Programming Language:** C++
- **Compiler:** Visual Studio and Code
- **Lines of Code:** 420+
- **Functions:** 17
- **Classes:** 1
- **Objects:** 234
- **Pointers:** 2
- **Difficulty Level:** Hard

**Enigma Machine Functionality**

The Enigma machine uses an electromechanical rotor mechanism to scramble the 26 letters of the alphabet. Each keypress changes the electrical connections between the keys and the lights, thereby transforming plain text into encoded ciphertext. The machine comprises several parts, including a keyboard, lamp board, rotors, and internal electronic circuitry.

**Working Principle**

1. **Keyboard and Lampboard Initialization:**
   - The keyboard contains 26 alphabets, each represented by a letter.
   - The lampboard also contains 26 alphabets, each corresponding to a lamp that illuminates when a key is pressed.

2. **Rotor Mechanism:**
   - The machine includes three rotors, each marked from 1 to 26. Each rotor has internal connections using pins for letter changes.
   - The rotors change the letter six times before it reaches the reflector.
   - The reflector interchanges the letter once, which then returns through the rotors and the plugboard before displaying the final encoded letter on the lampboard.

3. **Encoding and Decoding:**
   - The machine encodes a message by scrambling the letters using the rotor mechanism.
   - To decode the message, the same rotor configuration must be used.

**Simulation Implementation**

The C++ program simulates the Enigma machine's encoding and decoding process. The main components include:

1. **Decoder Class:**
   - Represents each part of the Enigma machine (keyboard, lampboard, rotors).
   - Contains attributes for data, left and right connections.

2. **Initialization Functions:**
   - Functions to initialize the keyboard, lampboard, and rotors.
   - Sets up the internal structure of the rotors.

3. **Cipher Function:**
   - Encodes the input text based on the rotor spins.
   - Converts the text to uppercase and processes each character through the rotors and reflector.

4. **Main Function:**
   - Prompts the user to input rotor spins and the text to encode.
   - Displays the encoded cipher text.

**Example Usage**

1. **User Input:**
   - Rotor 1 Spin: 7
   - Rotor 2 Spin: 3
   - Rotor 3 Spin: 9
   - Text to Encode: Hii Ghiyos ud Din (Tajikistan)

2. **Encoded Output:**
   - Cipher Text: IEI OSKS OYNDSM SDF ADO EANFE AODMMQK KAL QTREN KTKT

3. **Decoding:**
   - Using the same rotor spins to decode the cipher text will return the original text.

**Conclusion**

The Enigma machine project demonstrates the implementation of a historical cipher device using modern programming techniques. The project involved complex components such as rotors, reflectors, and plugboards, and required careful attention to detail to ensure accurate encoding and decoding. This simulation provides insights into the workings of the Enigma machine and showcases the importance of cryptographic techniques in securing communication.
