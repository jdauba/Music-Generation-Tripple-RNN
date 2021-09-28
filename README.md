# Music-Generation-Tripple-RNN
Neural Network generating "Avicii" style music melodies !

Dataset : small handmade dataset of ~300 MIDI music files, in the style of Avicii music

Architecture : considering a previous sequence of notes, 3 seperate RNN fuse at one point to predict :
- The pitch of the next note
- The duration of the next note
- The offset of the next note (time between previous and next note)
