# jouney-to-the-stars 

## design_brainstorm_v0.2a

##### Component/material list

- Raspberry Pi 3b or 3b+
  - Mircosd
- Motors
  - Linear Actuators (optional, for height adjustments)
  - Pan-Tilt HAT
  - 3-6 Motors depending on assembly/servo/frame limitations
- LEDs
  - 3 LED for alignment/calibration
  - 1 LED for alignment/calibration status
  - 1 LED for connectivity/update status
  - 1 LED for pointer marker/tip

### High level functions

calibrate()

get_location() 

get_orientation() -> orient()

connectivity_status()

get_status()

orient()

track() -> track_interval() -> smoothing(var%)

##### To Look into - Starmap project/library integration 

- Scripting in Stellarium

  - http://stellarium.org/

- [Star-api](https://github.com/HacktheUniverse/star-api) (currently down, see issue #48; potential to host locally if data source can be obtained)

  - Fork repository, and then include as git submodule in project
  - Issue #48: https://github.com/HacktheUniverse/star-api/issues/48
    - Dataset source (American Museum of Natural History): <http://research.amnh.org/users/abbott/dudata/> 

- [D3-Celestial](https://github.com/ofrohn/d3-celestial) 

- http://deepspacemap.com/#bookmark

- https://opendata.stackexchange.com/questions/6171/where-can-i-find-a-rest-api-of-stars-and-constellations

  - http://www.strudel.org.uk/lookUP/about.html
  - http://simbad.u-strasbg.fr/simbad/

  ​