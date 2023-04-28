**Variablen**

**extern**                      **intern**
> **Steuerung**
> UA_GB_del                 -->     :br
> UA_GB_enter               -->     :be
> UA_GB_prev                -->     :bp
> UA_GB_next                -->     :bn
> UA_GB_minus               -->     :bm

> UA_GB_strean              -->     :str
> UA_GB_edit                -->     :bs
> UA_GB_store               -->     :bh
> UA_GB_up                  -->     :bu
> UA_GB_down                -->     :bd

> UA_GB_01                  -->     :b1
> UA_GB_02                  -->     :b2
> UA_GB_03                  -->     :b3
> UA_GB_04                  -->     :b4
> UA_GB_05                  -->     :b5

> UA_GB_06                  -->     :b6
> UA_GB_07                  -->     :b7
> UA_GB_08                  -->     :b8
> UA_GB_09                  -->     :b9
> UA_GB_00                  -->     :b0


**Display**
> UA_GD_CursorX             <--     :gx
> UA_GD_CursorY             <--     :gy
> UA_GD_ShowCursor          <--     :gc
> UA_GD_Input               <--     :gi
> UA_GD_MoveCursor          <--     :gm

> UA_GD_ClearLayerGrid      <--     :gc
> UA_GD_GridLayerTextHue    <--     :gh
> UA_GD_SelectedLayer       <--     :gl
> UA_GD_LayerGridSize       <--     :ga


**Speicher Intern**
> :ws           waypoint selector integer
> :n            waypoint selector string
> [xyz]1-0      Waypoint Storage
> [c]1-0        Waypoint Checksum
> [xyz]         Waypoint integer
> [rst]         Waypoint string output
> w[xyz]s       Waypoint string sleep

> [opq]         Target integer
> [uvw]         Target string output
> w[xyz]t       Target string sleep

> :e            edit String Output
> :el           edit Load
> :es           edit Store
> :em           edit Memory
> :[abc]        edit XYZ Integer Input
> :e[xyz]       edit XYZ Math
> :e[abc]       edit XYZ String Output
> :en           edit Waypoint Integer
> :ew           Edit Waypoint String
