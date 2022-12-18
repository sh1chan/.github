# sh1chan - Shinigami Chan (死神ちゃん)

Mortal, and I want it to be simple and clear
```
/ - widgets (summary)
	/me    - 自分 ?
	/home  - home ?
	/group - group ?
		/cities
		/relations {friends,family,relatives}
	/...
```

Web UI Constructor - To interact with other applications
```
=> /workspaces/constructor/c/0

+---------+		+--------+		+---------+		+--------+
| sh1chan |	>	| jinja2 |	>	| ajax.js |	>	| render |
+---------+		+--------+		+---------+		+--------+

0. sh1chan	- application with dependencies and configurations
1. jinja2	- rendering the templates with configurations and static files
			{"HOST": "...", "PORT": "..."}
2. ajax.js	- talks to the main database to update its configurations
			{"HOST": "...", "PORT": "...", "app": "constructor", "route": "c", "page": 0}
3. render	- rendering the data from the database (application) to the templates
```

## Contributors

Just a tool not a FKN unicorn, `clone > RP` or create an `issue` so we can work on it
```
# Simple Example (Image processing tool)
python ipt.py -i <img> --crop 'x10:y20' -o <img_temp>

# UI (sh1chan)
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
