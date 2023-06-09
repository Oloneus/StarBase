**Variablen**

**Display**
> UA_GD_CursorX              <--     :CursorX
> UA_GD_CursorY              <--     :CursorY
> UA_GD_ShowCursor           <--     :ShowCursor
> UA_GD_Input                <--     :Input
> UA_GD_MoveCursor           <--     :MoveCursor

> UA_GD_ClearLayerGrid       <--     :ClearLayerGrid
> UA_GD_GridLayerTextHue     <--     :GridLayerTextHue
> UA_GD_SelectedLayer        <--     :SelectedLayer

**extern**                          **intern**
> **Steuerung**
> UA_GB_del                  -->     :br
> UA_GB_enter                -->     :be
> UA_GB_prev                 -->     :bp
> UA_GB_next                 -->     :bn
> UA_GB_minus                -->     :bm

> UA_GB_strean               -->     :str
> UA_GB_edit                 -->     :bs
> UA_GB_store                -->     :bh
> UA_GB_Select               -->     :bw
> UA_GB_Target               -->     :bt

> UA_GB_01                   -->     :1 
> UA_GB_02                   -->     :2 
> UA_GB_03                   -->     :3 
> UA_GB_04                   -->     :4 
> UA_GB_05                   -->     :5 

> UA_GB_06                   -->     :6 
> UA_GB_07                   -->     :7 
> UA_GB_08                   -->     :8 
> UA_GB_09                   -->     :9 
> UA_GB_00                   -->     :0 

> **Edit**                          **Storage Module**
> :wo                        -->     :i        Waypoint String Input
> :wn                        -->     :wn       Waypoint Number Integer
> :wl                        <->     :wl       Waypoint Load
> :ws                        <->     :ws       Waypoint Store
> :wi                        <--     :o        String Waypoint Output
> :id                        <--     :wpDs     String wp Description
> :in                        <--     :wpNs     String wp Number
> :r                         <--     :wpXs     String wp X
> :s                         <--     :wpYs     String wp Y
> :t                         <--     :wpZs     String wp Z
>                                    :w[00-FF] Waypoint String Storage

**Speicher Intern**
> :init         initialization memory
> :wn           waypoint selector integer

> :e            edit String Output
> :ei           edit Mode Initialize
> :em           edit Memory
> :esn          Str2Num
> :est          Str2Num Status (0-4)
> :[abcw]       edit int XYZN (Str2Num Out)
> :ewp          edit description (1/2)
> :wpd          Waypoint description
> :wpxN         Waypoint description memory
> :[xyzn]       edit int XYZN
> :e[xyzn]      edit XYZN Math
> :s[xyzn]      edit XYZN String Output

> [uvw]         Target string output
> w[xyz]t       Target string sleep