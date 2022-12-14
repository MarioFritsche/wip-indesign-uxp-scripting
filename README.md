# InDesign UXP - Samples

InDesign UXP Skripting-Beispiele. Für den produktiven Einsatz bedingt zu verwenden. Über Verbesserungsvorschläge würde ich mich sehr freuen. | InDesign UXP scripting examples. To be used conditionally for productive use. I would be very happy about suggestions for improvement.

## Dialog

<a href="https://github.com/MarioFritsche/wip-indesign-uxp-scripting/blob/main/Dialog/dialogColorSchema.idjs"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="17" height="17"/> [dialogSamples.idjs](https://github.com/MarioFritsche/wip-indesign-uxp-scripting/blob/main/Dialog/dialogSamples.idjs)

**Color-Schema**
![This is an image](/src/img/screen_dialog.png)
Je nachdem, welches Farbmotiv in InDesign gewählt worden ist (Voreinstellungen -> Benutzeroberfläche -> Farbmotiv), können Farben im Dialog-Fenster festgelegt werden.

```
function PreferColors(prefersColor) {
switch (preferscolorscheme) {
    case 1.0:
    ...

// 1.0 => Hell, 0.51 => Mittelhell, 0.5 => Mitteldunkel, 0.0 => Dunkel
```
