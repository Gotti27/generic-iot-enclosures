# generic-iot-enclosures
A collection of 3D-printable enclosures and boxes for personal IoT projects 

## Configuration
Append this to your local gitconfig
```
[diff "zip"]
	textconv = unzip -c -a
[core]
	attributesfile = ~/.gitattributes
[filter "zippey"]
	smudge = scripts/zippey.py d
```

