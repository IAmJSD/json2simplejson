# json2simplejson
A simple monkey patcher in order to make things that run using the standard "json" library (such as discord.py) use the quicker "simplejson" library.

In order to patch, simply call the patch function:
```py
import json2simplejson
json2simplejson.patch()
```
