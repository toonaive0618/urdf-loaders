# urdf-loaders

URDF loading code in both [C# for Unity](./unity/Assets/URDF-Loader/) and [Javascript for THREE.js](./javascript/), as well as example [JPL ATHLETE](https://www-robotics.jpl.nasa.gov/systems/system.cfm?System=11) URDF files

[Demo Here!](https://gkjohnson.github.io/urdf-loaders/javascript/example/index.bundle.html)

![Example](./unity/Assets/docs/asset%20store/all-urdfs.png)

### Flipped Models

The `_flipped` variants of the URDF ATHLETE models invert the revolute joint axes to model ATHLETE in a configuration with the legs attached to the bottom of the chassis.

### Gotchas

The loaders support the necessary subset of the [URDF spec](http://wiki.ros.org/urdf/XML) to load the ATHLETE URDF and meshes. Specifically the code only supports fixed and revoluate joints, as well as loading `.STL` mesh files at the moment.

# LICENSE

The software is available under the [Apache V2.0 license](../LICENSE.txt).

Copyright © 2018 California Institute of Technology. ALL RIGHTS
RESERVED. United States Government Sponsorship Acknowledged. Any
commercial use must be negotiated with with Office of Technology
Transfer at the California Institute of Technology. This software may
be subject to U.S. export control laws. By accepting this software,
the user agrees to comply with all applicable U.S. export laws and
regulations. User has the responsibility to obtain export licenses,
or other export authority as may be required before exporting such
information to foreign countries or providing access to foreign
persons. Neither the name of Caltech nor its operating division, the
Jet Propulsion Laboratory, nor the names of its contributors may be
used to endorse or promote products derived from this software
without specific prior written permission.
