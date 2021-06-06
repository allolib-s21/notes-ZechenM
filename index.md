# Notes from Zechen Ma

* Added runtime warning features for setting an internal parameter that does not match with any predefined parameters in the class definition
  * https://github.com/allolib-s21/demo1-ZechenM/blob/master/allolib/src/scene/al_PolySynth.cpp
  * Line 388 in the code from the above link
* Integrated three instruments PluckedString, SquareWave, and SineEnv for making a Chinese folk music, "what the Pipa says"
  * The dominant instrument for playing the melody is called Pipa, where its timbre is emulated by the PluckedString 
  * SquareWave is for playing the chord progression
  * SineEnv is specifically for adding more layers by playing root and fifth notes during the third repetition of the main melody
  * https://github.com/allolib-s21/demo1-ZechenM/blob/master/WTPS_pl-pan.cpp
