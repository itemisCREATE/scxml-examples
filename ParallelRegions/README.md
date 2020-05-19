# ParallelRegions 

![image](ParallelRegions_0.png)

```xml
<?xml version="1.0" encoding="UTF-8"?>
<scxml xmlns="http://www.w3.org/2005/07/scxml" version="1.0" datamodel="ecmascript" name="ParallelRegions">
	<parallel>
	<state id="main_region">
		<initial>
			<transition target="StateAA" type="internal" >
			</transition>
		</initial>
		<state id="StateAA">
			<transition event="e"  target="StateAB">
			</transition>
		</state>
		<state id="StateAB">
		</state>
	</state>
	<state id="second_region">
		<initial>
			<transition target="StateBA" type="internal" >
			</transition>
		</initial>
		<state id="StateBA">
			<transition event="e"  target="StateBB">
			</transition>
		</state>
		<state id="StateBB">
		</state>
	</state>
	</parallel>
</scxml>
```
