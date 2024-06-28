# Polyphonic Pioneer
Polyphonic Pioneer allows users to upload a MIDI file of their favorite song. The app parses the file and uses Markov Chains to analyze the notes and their durations in parallel. This enables the app to generate a new melody inspired by the original song. The result is a unique, algorithmically generated composition that maintains the essence of the original music while introducing fresh, creative variations.

## Front End:
For the frontend, I utilized React to create an intuitive and user-friendly interface. The application is hosted on Firebase, ensuring smooth deployment and reliable performance. Here are some key features of the frontend:
- User Interface: Designed to be simple and accessible, allowing users to easily upload their MIDI files and interact with the generated melodies.
- File Upload: Users can drag and drop or select MIDI files from their device, which are then sent to the backend for processing.
- Audio Rendering: Once the new melody is generated, an audio player is embedded in the interface, enabling users to listen to the algorithmically created music.

## Back End:
On the backend, I developed the server using Flask. This handles the core functionality of parsing the MIDI files, executing the Markov Chain analysis, and generating the new melodies. Here are some key features of the backend:
- MIDI Parsing: The backend parses the uploaded MIDI files to extract the notes and their durations.
- Markov Chain Analysis: Utilizes Markov Chains to analyze the extracted notes and their durations in parallel, forming the basis for generating new melodies.
- Melody Generation: Based on the analysis, the backend generates a new melody that is inspired by the original song while introducing creative variations.
- Audio Conversion: Converts the generated melody into an audio format that can be played back on the frontend.
