# The Mad Language

## By Wisam Idris

This MAD Language 😡
Is Basic Language And Thanks


How To Run

```
python ./shell.py
```
And After It Do That To Run A File
```
mad >> WALK("example.cr");
```
```
DODY oopify(prefix) -> prefix + "oop"

DODY join(elements, separator)
	MAV result = ""
	MAV len = LEN(elements)

	KOOL i = 0 TO len SO_ON
		MAV result = result + elements/i
		IF i != len - 1 SO_ON MAV result = result + separator
	AND_SO_FORTH

	GIVE result
AND_SO_FORTH

DODY map(elements, func)
	MAV new_elements = []

	KOOL i = 0 TO LEN(elements) SO_ON
		APPAND_SO_FORTH(new_elements, func(elements/i))
	AND_SO_FORTH

	GIVE new_elements
AND_SO_FORTH

GETTHATINTHECONSOLE("Greetings universe!")

KOOL i = 0 TO 5 SO_ON
	GETTHATINTHECONSOLE(join(map(["l", "sp"], oopify), ", "))
AND_SO_FORTH
```

All Thanks To CodePulse

https://www.youtube.com/playlist?list=PLZQftyCk7_SdoVexSmwy_tBgs7P0b97yD
