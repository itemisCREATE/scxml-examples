# FinalState 

![image](FinalState_0.png)

```xml
<?xml version="1.0" encoding="UTF-8"?>
<scxml xmlns="http://www.w3.org/2005/07/scxml" version="1.0" datamodel="ecmascript" name="FinalState">
	<state id="main_region">
		<initial>
			<transition target="myState" type="internal" >
			</transition>
		</initial>
		<state id="myState">
			<transition   target="final_0">
			</transition>
		</state>
		<final id="final_0"/>	
	</state>
</scxml>
```
