# Circle of Fifths & Dynamic Fretboard

This project is a single-page, browser-based web application designed to visualize music theory and map it directly to the guitar fretboard. By selecting major or minor keys from the interactive Circle of Fifths, the application instantly calculates and highlights the corresponding notes and scales on the fretboard.

## Features

* **Interactive Circle of Fifths:** Select your key by clicking on the major or minor slices of the circle. The center information panel instantly displays the relative minor/major keys and the number of accidentals (sharps/flats).
* **Dynamic Guitar Fretboard:** Notes belonging to the selected key are instantly highlighted across the fretboard. Root notes are emphasized with a distinct, glowing design.
* **Tuning System:** 
  * **Presets:** Standard, Drop D, Half-Step Down, and DADGAD.
  * **Custom Tuning:** Create your own custom tuning by independently selecting the specific note for each of the 6 strings.
* **Enharmonic Accuracy:** Intelligently displays note names with the mathematically correct sharps (`♯`) or flats (`♭`) depending on the context of the selected key.

## Technologies Used

* HTML5
* CSS3 (Flexbox, CSS Variables)
* Vanilla JavaScript (ES6+)

