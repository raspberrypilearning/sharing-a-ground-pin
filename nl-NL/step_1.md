There are only 8 **GND** pins on a Raspberry Pi Pico. This means that if you want to use more than 8 components, you will need to share a **GND**. Hier is een methode om een aardingspin te delen:

Je hebt nodig:
+ verbindingsdraden met pin-bus aansluiting
+ wat aluminiumfolie, geleidende tape of een ander geleidend materiaal
+ plakband

**Step 1**: Create a strip of kitchen foil or use your other conductive material.

**Stap 2**: Sluit een **GND** pin aan op je aluminiumfolie (gebruik plakband om vast te zetten).

![A Raspberry Pi Pico with a ground pin connected to a piece of kitchen foil.](images/step-one.jpeg){:width="500px"}

**Stap 3**: Bij het toevoegen van een component aan de Raspberry Pi Pico, verbind de **positieve** uiteinden met een **GP** pin en de **negatieve** uiteinden met het aluminiumfolie.

![A Raspberry Pi Pico with a ground pin connected to a piece of kitchen foil. Er is ook een zoemer bevestigd met het positieve uiteinde op de GP5-pin en het negatieve uiteinde op het aluminiumfolie geplakt.](images/step-three.jpeg){:width="500px"}

**Stap 4**: Zorg er bij het toevoegen van nog meer componenten voor dat het **positieve** uiteinde is aangesloten op een **GP** pin op de Raspberry Pi Pico en dat het **negatieve** uiteinde op het aluminiumfolie is geplakt.

![A Raspberry Pi Pico with a ground pin connected to a piece of kitchen foil. Een zoemer en een LED zijn ook bevestigd met de positieve uiteinden op de GP-pinnen en de negatieve uiteinden op het aluminiumfolie geplakt.](images/step-four.jpeg){:width="500px"}