# ALPAPAAM

A project to create an "As Low-Poly As Possible Anatomically Accurate 3D Model". Thus the name. Yeah. I'm bad at names.

## Rationale

There are many medically-accurate 3D models out there; this is not one.

This model emphasises on:

- Minimum viable detail for artists: If a muscle isn't really relevant for drawing, then it isn't there
- Very low-poly resolution: this should run without troubles even on the lowest-end PC
- Open-source: everyone is invited to contribute
- Permissive License: feel free to use this model for anything, no attribution necessary (though sending me a note so I can see what you've done with it is welcome)
- Potentially provide a way to export the modified model for further customization, ala [MakeHuman](http://www.makehuman.org/) or [ManuelBastioniLab](http://www.manuelbastioni.com/manuellab.php).

[Here's a 3D preview of the model](https://sketchfab.com/models/b08dbc53a19c423c8414760e395342a9/)


## Planned features

A check denotes that the feature has been implemented.

- [x] Model A skeleton
- [x] Model muscles
- [x] Model subcutaneous fat
- [x] Model visceral fat
- [x] Model external skin with the best possible edge loops while staying as low poly as possible
- [x] Model main internal organ and genitals
- [ ] Rig Bones to rotate accurately
- [ ] Rig Muscles to follow bones movement
- [ ] Rig Muscles to deform accurately according to bones movement
- [ ] Rig IK with optional FK
- [ ] Control helpers for fingers, toes, and foot
- [ ] Provide sliders for muscles definition
- [ ] Provide sliders for fat deposits (belly, etc)
- [ ] Provide sliders for gender
- [ ] Provide deformation sliders to get a toony aspect
- [ ] Have the skin follow all deformations
- [ ] Provide the way to "bake" the skin with deformations into a sculptable character, conserving the rig

## License

Copyright (c) 2016 Jad Sarout
Permission is hereby granted, free of charge, to any person obtaining a copy of this model and associated documentation files (the "Model"), to deal in the Model without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Model, and to permit persons to whom the Model is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Model.
THE MODEL IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Thanks
 
 - Olson from getblended.org who's provided much needed advice and helpful examples
