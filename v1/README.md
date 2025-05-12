## BOM

### With an inductive Z probe sensor

#### For the X carriage coupling adapter
- **Follow [Print settings](#-print-settings) below**
- `adapter.stl` and `probe_holder.stl`
- 6x - 12mm x 3mm neodymium magnets (recommended to be N42 or N52, weaker ones won't hold the printhead securely enough)
- 1x inductive sensor - fits up to an 18mm diameter sensor
- 1x 17mm M3 bolt - to secure the inductive sensor
- The adapter is the only piece that has a recommended high resolution layer height and ironing. You could have issues with mating if the adapter surface is not flat or if the half sphere is not as close to round as possible.

#### For each printhead
- **Follow [Print settings](#-print-settings) below**
- `dock_left_hand.stl`
- `extruder_mount.stl`
- `retainer.stl`
- `shroud.stl`
- `hotend_cable_holder.stl`
- E3D V6 
- 5015 fan
- 2x - M3 heat set insert
- 3x - 12mm x 3mm neodymium magnets
- **The lengths below are what I used but you can easily use slightly different lengths based on what you have available**
- 23mm M3 bolt - for attaching part cooling fan
- 2x - 17mm M3 bolt - for attaching retainer to extruder mount
- 4x - 8mm M3 bolt - for attaching part cooling fan shroud and hotend cable holder

### Bring your own Z end stop solution
Same parts as above but instead of `adaptor.stl` and `probe_holder.stl` print `adapter_no_probe_holder.stl` 

## Print settings
- **Files are already in the correct orientation**

| File | Layer height | Walls (0.4mm nozzle) | Infill | Support | Support type | Ironing |
|--|--|--|--|--|--|--|
| `adapter.stl` | 0.1mm | 4 | 30% | :white_check_mark: | Normal | :white_check_mark: |  |
| `probe_holder.stl` | 0.2mm | 3 | 30% | :x: | :x: | :x: |
| `adapter_no_probe_holder.stl` | 0.1mm | 4 | 30% | :white_check_mark: | Normal | :white_check_mark: |
| `dock_left_hand.stl` | 0.2mm | 2 | 30% | :white_check_mark: | Tree | :x: |
| `dock_right_hand.stl` | 0.2mm | 2 | 30% | :white_check_mark: | Tree | :x: |
| `extruder_mount.stl` | 0.2mm | 4 | 30% | :x: | Normal | :x: |
| `retainer.stl` | 0.2mm | 4 | 30% | :x: | Normal | :x: |

These files don't have any specific print setting requirements:
- `hotend_cable_holder.stl` 
- `shroud.stl`
## Assembly 

**Assembling the adapter:**
- Attach `adapter.stl` and `probe_holder.stl` together with a bit of super glue
- Insert 2x magnets into each of the holes on the adapter - you might need super glue to secure them but it should be press fit
- Insert inductive sensor into `probe_holder.stl` and secure with the 17mm M3 bolt

**Assembling the extruder mount:**
 - Insert 1x magnet into each of the holes on the adapter - you might need super glue to secure them but it should be press fit
 - Take care to match the polarity, but if you get it wrong -  there are holes on the other side you can use to push out the magnet
 - Melt heat set inserts into "bridge" of the extruder mount, secure hotend with `retainer.stl` and 17mm M3 bolts
 - Self tap 23mm M3 bolt to attach 5015 fan
 - Self tap 8mm M3 bolt to attach `shroud.stl` and `hotend_cable_holder.stl`
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU5OTIyMTE4NywtNzMzODAwMzk5LC0xMz
QwNzA5NDc0LC02NDM2MzY0ODYsMTk1NDc5MDAxOSwtMjQyMjEx
Nzk3LDIxNDA4MDA3ODMsMzIyNDM2OTUsLTExOTY0NjczNDVdfQ
==
-->