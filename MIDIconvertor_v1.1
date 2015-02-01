/*  MIDI Convertor 1.1
*   Authors: Pancake Lizard, Shermdog, and ryanman
*   Last Update: 29/1/2015
*   
*   Hardware: Arduino MEGA 2560
*             Farfisa VIP-233, 345 and 370 bass pedals
*/

int state = 0;
int lastNote = 0;

void setup() {
  Serial.begin(31250);
}

void loop() {
  
  if (analogRead(0) > 1020) {
    delay(20);
    if (analogRead(0) > 1020) {
      MIDInote(24); // C-2
    }
  }
  else if (analogRead(1) > 1020) {
    delay(20);
    if (analogRead(1) > 1020) {
      MIDInote(25);
    }
  }
  else if (analogRead(2) > 1020) {
    delay(20);
    if (analogRead(2) > 1020) {
      MIDInote(26); 
    }
  }
  else if (analogRead(3) > 1020) {
    delay(20);
    if (analogRead(3) > 1020) {
      MIDInote(27);
    }
  }
  else if (analogRead(4) > 1020) {
    delay(20);
    if (analogRead(4) > 1020) {
      MIDInote(28);
    }
  }
  else if (analogRead(5) > 1020) {
    delay(20);
    if (analogRead(5) > 1020) {
      MIDInote(29);
    }
  }
  else if (analogRead(6) > 1020) {
    delay(20);
    if (analogRead(6) > 1020) {
      MIDInote(30); 
    }
  }
  else if (analogRead(7) > 1020) {
    delay(20);
    if (analogRead(7) > 1020) {
      MIDInote(31);
    }
  }
  else if (analogRead(8) > 1020) {
    delay(20);
    if (analogRead(8) > 1020) {
      MIDInote(32); 
    }
  }
  else if (analogRead(9) > 1020) {
    delay(20);
    if (analogRead(9) > 1020) {
      MIDInote(33);
    }
  }
  else if (analogRead(10) > 1020) {
    delay(20);
    if (analogRead(10) > 1020) {
      MIDInote(34);
    }
  }
  else if (analogRead(11) > 1020) {
    delay(20);
    if (analogRead(11) > 1020) {
      MIDInote(35);
    }
  }
  else {
    MIDImessage(128, lastNote, 127);
    state = 0;
  }
  
}
  
// Determining what to do  
void MIDInote(int myNote) { // Takes in the triggered note's MIDI number
  if (state == 0) { // Checks to see if note is playing
    MIDImessage(144, myNote, 127); // Sends MIDI note ON, Note value, and velocity to MIDImessage object
    state = 1; // changes play status to ON
    lastNote = myNote; // saves current note as last note played
  }
  else if ((state == 1) && (myNote = lastNote)) { // if note is already playing and it is the same, do nothing
  }
  else if ((state == 1) && (myNote != lastNote)) { // if note is already playing and a new one is triggered...
    MIDImessage(144, myNote, 127); // play new note
    lastNote = myNote; 
  }
  else {
    state = 0;
  }

}

// send MIDI message 
void MIDImessage(int MIDIcommand, int MIDInote, int MIDIvelocity) { 
  Serial.write(MIDIcommand); // send note on or note off command 
  Serial.write(MIDInote); // send pitch data 
  Serial.write(MIDIvelocity); // send velocity data 
}

/* Ryanman's contribution for a possible 2.0 version
#define THRESHOLD_ON   1020
#define MIN_SAMPLES    3
#define DEBOUNCE_DELAY 5
#define NUM_KEYS       12
#define MIDI_OFFSET    24
void loop()
{
  int samples;
  int chan;
  
  for (chan = 0; chan < NUM_KEYS; ++chan)
  {
    samples = 0;
    if (readAnalog(chan) > THRESHOLD_ON)
    {
      do
      {
        samples++;
        Sleep(DEBOUNCE_DELAY);
      } while (readAnalog(chan) > THRESHOLD_ON && samples < MIN_SAMPLES);
      
      if (samples >= MIN_SAMPLES)
      {
        MIDInote(chan + MIDI_OFFSET);
        return;
      }
    }
  }
  
  //take action here for no button pressed
  MIDImessage(128, lastNote, 127);
  state = 0;
}
*/
