Polyphonic Pioneer
---
Polyphonic Pioneer allows users to upload a MIDI file of their favorite song. The app parses the file and uses Markov Chains to analyze the notes and their durations in parallel. This enables the app to generate a new melody inspired by the original song. The result is a unique, algorithmically generated composition that maintains the essence of the original music while introducing fresh, creative variations.

For the frontend, I utilized React to create an intuitive and user-friendly interface. The application is hosted on Firebase, ensuring smooth deployment and reliable performance. Users can  upload their MIDI files and an audio of the generated melody is rendered for the user to listen to.

On the backend, I developed the server using Flask. This handles the core functionality of parsing the MIDI files, executing the Markov Chain analysis, and generating the new melodies. Flask's lightweight and flexible framework allowed for efficient handling of the data processing and algorithm execution, ensuring the app's responsiveness and robustness.
