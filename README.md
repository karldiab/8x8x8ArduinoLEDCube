# ArduinoPowered8x8x8RGBLEDCube
Based off of the Arduino Mega 2560 code for the LED cube project at http://www.theledcube.com/source-code/ 

This project features over new display routines and enhanced controllability using external buttons

**Routines :** (Updated 9 Sept)


**Spirals**

Fluxing spirals on cube faces with switching color gradients

**Rubiks Cube**

Rubiks cube scrambles itself in a random number of steps then solves itself

**Folder** (default)

**Display Text**

Can display any ASCII message as a scrolling colored letters on the side cube faces, or from an array of messages randomly.

**Hypercube**

The tesseract demands respect

**Glowing Cube**

Sparkling particles run along the cube's edges

**Sin Wave** (default)

Cool moving sine wave patterns. Probably my favorite animation

**Color Wheel** (default)

**Bouncy** (default)

**Fireworks** (default)

**Dancing Cube**

Wireframe cube grows and shrinks in random colors

**Wipeout** (default)

**Harlem Shake** (default)

**Rain**

Slightly modified default rain animation

        Spirals(routineSettings[currentRoutine]);
        break;
      }
      case 2 : 
      {
        rubiksCube(routineSettings[currentRoutine]);
        break;
      }
      case 3 : 
      {
        rainVersionTwo(routineSettings[currentRoutine]);
        clean(); 
        break;
      }
      case 4 : 
      {
        folder(routineSettings[currentRoutine]);
        clean();
        break;
      }
      case 5 : 
      {
        wipe_out();
        clean();
        break;
      }
      case 6 : 
      {
        glowingCube(routineSettings[currentRoutine]);
        break;
      }
      case 7 : 
      {
        color_wheelTWO();
        clean();
        break;
      }
      case 8 : 
      {
        harlem_shake();
        clean();
        break;
      }
      case 9 :
      {
        bouncyvTwo();
        clean();
        break;
      }
      case 10 :
      {
        fireworks(5,15,0,routineSettings[currentRoutine]);
        break;
      }
      case 11 : 
      {
        dancingCube(routineSettings[currentRoutine]);
        break;
      }
      case 12 :
      {
        hyperCube(routineSettings[currentRoutine]);
        clean();
      }
      case 13 :
      {
        sinwaveTwo();
        clean();
      }
      case 14 :
      {
        displayTextRoutine(routineSettings[currentRoutine]);