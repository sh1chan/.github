Web UI Constructor - To interact with other applications

## Contributors

Just a tool not a FKN unicorn, `clone > RP` or create an `issue` so we can work on it
```
# Simple Example (Image processing tool)
python ipt.py -i <img> --crop 'x10:y20' -o <img_temp>

# UI
+---------------------------------------------------+
|                      Nav Top                      |
+----------+----------------------------+-----------+
| Nav Left |                            | Nav Right |
+----------+                            +-----------+
|   Tools  |                            |  Options  |
+----------+                            +-----------+
| > Image  |                            |  > Crop   | > *Crop Options*
+----------+       <Box Image />        +-----------+
|                                       |  Actions  |
|                                       +-----------+
|                                       |  > Post   | > *Post Options*
|                                       |  > Exec   | > *Execute Options*
|                                       +-----------+
|                                                   |
+---------------------------------------------------+

Application may do a Request to other servers or Execute the command
```

## License

D_WTF_YW
<br />
Copyright (c) 2022 Nodiru Gaji
