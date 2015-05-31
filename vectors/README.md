This directory holds the vectors that are extruded and manipulated to form the 3D model. They are created in Adobe Illustrator and exported for MAXON Cinema 4D.

- **`headphone-holder.ai`** is the main Illustrator vector file. Changes are made here first.

- **`headphone-holder-c4d.ai`** is an output vector with all of the base/guide shapes and strokes removed. This is saved as an Illustrator 8 file for compatibility.

- **`headphone-holder-c4d-div.ai`** is another output vector &ndash; that is actually used &ndash; which uses only straight lines. Illustrator's path simplifying tool is useless, so editing this is a pain. The curves must be **div**ided like this as Cinema does a poor job otherwise.
