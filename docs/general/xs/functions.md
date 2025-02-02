*Written by: Alian713*
<div id="hide-toc-elements"></div>
---

## 1. Rules

### 1.1. xsDisableRule

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsDisableRule(string ruleName)`

Parameters:

1.  `#!cpp string ruleName`: The name of the rule to disable

Disables the given rule.

### 1.2. xsDisableRuleGroup

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsDisableRuleGroup(string ruleGroupName)`

Parameters:

1.  `#!cpp string ruleGroupName`: The name of the rule group to disable

Disables all the rules in the given rule group

### 1.3. xsDisableSelf

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsDisableSelf()`


Disables the rule this function is called inside. Cannot be used outside of a rule's body!

### 1.4. xsEnableRule

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsEnableRule(string ruleName)`

Parameters:

1.  `#!cpp string ruleName`: The name of the rule to enable

Enables the given rule.

### 1.5. xsEnableRuleGroup

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsEnableRuleGroup(string ruleGroupName)`

Parameters:

1.  `#!cpp string ruleGroupName`: The name of the rule group to enable

Enables all the rules in the given rule group

### 1.6. xsIsRuleEnabled

Returning Type: `#!cpp bool`

Prototype: `#!cpp bool xsIsRuleEnabled(string ruleName)`

Parameters:

1.  `#!cpp string ruleName`: The name of the rule to check

Returns true if the rule is enabled, else returns false.

### 1.7. xsIsRuleGroupEnabled

Returning Type: `#!cpp bool`

Prototype: `#!cpp bool xsIsRuleGroupEnabled(string ruleGroupName)`

Parameters:

1.  `#!cpp string ruleGroupName`: The name of the rule group to check

Returns true, if all the rules in the given rule group are enabled

### 1.8. xsSetRuleMaxInterval

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsSetRuleMaxInterval(string ruleName, int interval)`

Parameters:

1.  `#!cpp string ruleName`: The name of the rule to set the max interval of
2.  `#!cpp int interval`: The new max interval of the rule

Sets the max interval of the given rule.

### 1.9. xsSetRuleMaxIntervalSelf

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsSetRuleMaxIntervalSelf(int interval)`

Parameters:

1.  `#!cpp int interval`: The new max interval of the rule

Sets the max interval of the rule this function is called inside. Cannot be used outside of a rule's body!

### 1.10. xsSetRuleMinInterval

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsSetRuleMinInterval(string ruleName, int interval)`

Parameters:

1.  `#!cpp string ruleName`: The name of the rule to set the min interval of
2.  `#!cpp int interval`: The new min interval of the rule

Sets the min interval of the given rule.

### 1.11. xsSetRuleMinIntervalSelf

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsSetRuleMinIntervalSelf(int interval)`

Parameters:

1.  `#!cpp int interval`: The new min interval of the rule

Sets the min interval of the rule this function is called inside. Cannot be used outside of a rule's body!

### 1.12. xsSetRulePriority

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsSetRulePriority(string ruleName, int priority)`

Parameters:

1.  `#!cpp string ruleName`: The name of the rule to set the priority of
2.  `#!cpp int priority`: The new priority of the rule

Sets the priority of the given rule.

### 1.13. xsSetRulePrioritySelf

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsSetRulePrioritySelf(int priority)`

Parameters:

1.  `#!cpp int priority`: The new priority of the rule

Sets the priority of the rule this function is called inside. Cannot be used outside of a rule's body!

## 2. Vectors

### 2.1. xsVectorGetX

Returning Type: `#!cpp float`

Prototype: `#!cpp float xsVectorGetX(vector v)`

Parameters:

1.  `#!cpp vector v`: The vector to get the X coordinate of

The X coordinate of the vector given.

### 2.2. xsVectorGetY

Returning Type: `#!cpp float`

Prototype: `#!cpp float xsVectorGetY(vector v)`

Parameters:

1.  `#!cpp vector v`: The vector to get the Y coordinate of

The Y coordinate of the vector given.

### 2.3. xsVectorGetZ

Returning Type: `#!cpp float`

Prototype: `#!cpp float xsVectorGetZ(vector v)`

Parameters:

1.  `#!cpp vector v`: The vector to get the Z coordinate of

The Z coordinate of the vector given.

### 2.4. xsVectorLength

Returning Type: `#!cpp float`

Prototype: `#!cpp float xsVectorLength(vector v)`

Parameters:

1.  `#!cpp vector v`: The vector to calculate the length of

Returns the length of the given vector.

### 2.5. xsVectorNormalize

Returning Type: `#!cpp vector`

Prototype: `#!cpp vector xsVectorNormalize(vector v)`

Parameters:

1.  `#!cpp vector v`: The vector to normalise

Returns the normalised vector in the direction of the given vector.

### 2.6. xsVectorSet

Returning Type: `#!cpp vector`

Prototype: `#!cpp vector xsVectorSet(float x, float y, float z)`

Parameters:

1.  `#!cpp float x`: The value to set the X coordinate to
2.  `#!cpp float y`: The value to set the Y coordinate to
3.  `#!cpp float z`: The value to set the Z coordinate to

Returns a vector with the given X, Y and Z components.

### 2.7. xsVectorSetX

Returning Type: `#!cpp vector`

Prototype: `#!cpp vector xsVectorSetX(vector v, float x)`

Parameters:

1.  `#!cpp vector v`: The vector to modify the X coordinate of
2.  `#!cpp float x`: The value to set the X coordinate to

Returns a new vector with the X component of the given vector changed to the given value. Note: This function DOES NOT modify the vector given as the parameter!

### 2.8. xsVectorSetY

Returning Type: `#!cpp vector`

Prototype: `#!cpp vector xsVectorSetY(vector v, float y)`

Parameters:

1.  `#!cpp vector v`: The vector to modify the Y coordinate of
2.  `#!cpp float y`: The value to set the Y coordinate to

Returns a new vector with the Y component of the given vector changed to the given value. Note: This function DOES NOT modify the vector given as the parameter!

### 2.9. xsVectorSetZ

Returning Type: `#!cpp vector`

Prototype: `#!cpp vector xsVectorSetZ(vector v, float z)`

Parameters:

1.  `#!cpp vector v`: The vector to modify the Z coordinate of
2.  `#!cpp float z`: The value to set the Z coordinate to

Returns a new vector with the Z component of the given vector changed to the given value. Note: This function DOES NOT modify the vector given as the parameter!

## 3. Arrays

### 3.1. xsArrayCreateBool

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayCreateBool(int size, bool defaultValue, string uniqueName)`

Parameters:

1.  `#!cpp int size`: The length of the array to create
2.  `#!cpp bool defaultValue`: The default value to initialise all the values in the array to
3.  `#!cpp string uniqueName`: A unique name of the created array

Creates an array of type bool and returns its ID.

### 3.2. xsArrayCreateFloat

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayCreateFloat(int size, float defaultValue, string uniqueName)`

Parameters:

1.  `#!cpp int size`: The length of the array to create
2.  `#!cpp float defaultValue`: The default value to initialise all the values in the array to
3.  `#!cpp string uniqueName`: A unique name of the created array

Creates an array of type float and returns its ID.

### 3.3. xsArrayCreateInt

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayCreateInt(int size, int defaultValue, string uniqueName)`

Parameters:

1.  `#!cpp int size`: The length of the array to create
2.  `#!cpp int defaultValue`: The default value to initialise all the values in the array to
3.  `#!cpp string uniqueName`: A unique name of the created array

Creates an array of type int and returns its ID.

### 3.4. xsArrayCreateString

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayCreateString(int size, string defaultValue, string uniqueName)`

Parameters:

1.  `#!cpp int size`: The length of the array to create
2.  `#!cpp string defaultValue`: The default value to initialise all the values in the array to
3.  `#!cpp string uniqueName`: A unique name of the created array

Creates an array of type String and returns its ID.

### 3.5. xsArrayCreateVector

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayCreateVector(int size, vector defaultValue, string uniqueName)`

Parameters:

1.  `#!cpp int size`: The length of the array to create
2.  `#!cpp vector defaultValue`: The default value to initialise all the values in the array to
3.  `#!cpp string uniqueName`: A unique name of the created array

Creates an array of type Vector and returns its ID.

### 3.6. xsArrayGetBool

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayGetBool(int arrayID, int index)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to get the value from
2.  `#!cpp int index`: The index to get the value of

Gets and returns the value of the given bool array at the specifed index.

### 3.7. xsArrayGetFloat

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayGetFloat(int arrayID, int index)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to get the value from
2.  `#!cpp int index`: The index to get the value of

Gets and returns the value of the given float array at the specifed index.

### 3.8. xsArrayGetInt

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayGetInt(int arrayID, int index)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to get the value from
2.  `#!cpp int index`: The index to get the value of

Gets and returns the value of the given int array at the specifed index.

### 3.9. xsArrayGetSize

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayGetSize(int arrayID)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to get the length of

Returns the length of the given array.

### 3.10. xsArrayGetString

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayGetString(int arrayID, int index)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to get the value from
2.  `#!cpp int index`: The index to get the value of

Gets and returns the value of the given String array at the specifed index.

### 3.11. xsArrayGetVector

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayGetVector(int arrayID, int index)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to get the value from
2.  `#!cpp int index`: The index to get the value of

Gets and returns the value of the given Vector array at the specifed index.

### 3.12. xsArrayResizeBool

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayResizeBool(int arrayID, int newSize)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to resize
2.  `#!cpp int newSize`: The new size of the array

Resizes the the given bool array to the specifed size and returns 1.

### 3.13. xsArrayResizeFloat

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayResizeFloat(int arrayID, int newSize)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to resize
2.  `#!cpp int newSize`: The new size of the array

Resizes the the given float array to the specifed size and returns 1.

### 3.14. xsArrayResizeInt

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayResizeInt(int arrayID, int newSize)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to resize
2.  `#!cpp int newSize`: The new size of the array

Resizes the the given int array to the specifed size and returns 1.

### 3.15. xsArrayResizeString

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayResizeString(int arrayID, int newSize)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to resize
2.  `#!cpp int newSize`: The new size of the array

Resizes the the given String array to the specifed size and returns 1.

### 3.16. xsArrayResizeVector

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArrayResizeVector(int arrayID, int newSize)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to resize
2.  `#!cpp int newSize`: The new size of the array

Resizes the the given Vector array to the specifed size and returns 1.

### 3.17. xsArraySetBool

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArraySetBool(int arrayID, int index, bool value)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to set the value in
2.  `#!cpp int index`: The index to set the value of
3.  `#!cpp bool value`: The new value to set

Sets the valuat the specified indedx e of the given bool arrindex to the provided value and returns 1.

### 3.18. xsArraySetFloat

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArraySetFloat(int arrayID, int index, float value)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to set the value in
2.  `#!cpp int index`: The index to set the value of
3.  `#!cpp float value`: The new value to set

Sets the valueat the specified indedx  of the given float array to the provided value and returns 1.

### 3.19. xsArraySetInt

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArraySetInt(int arrayID, int index, int value)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to set the value in
2.  `#!cpp int index`: The index to set the value of
3.  `#!cpp int value`: The new value to set

Sets the valat the specified indedx ue of the given int arrindex to the provided value and returns 1.

### 3.20. xsArraySetString

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArraySetString(int arrayID, int index, string value)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to set the value in
2.  `#!cpp int index`: The index to set the value of
3.  `#!cpp string value`: The new value to set

Sets the value at the specified indedx of the given String array to the provided value and returns 1.

### 3.21. xsArraySetVector

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsArraySetVector(int arrayID, int index, vector value)`

Parameters:

1.  `#!cpp int arrayID`: The ID of the array to set the value in
2.  `#!cpp int index`: The index to set the value of
3.  `#!cpp vector value`: The new value to set

Sets the value at the specified indedx of the given Vector array to the provided value and returns 1.

## 4. Maths

### 4.1. abs

Returning Type: `#!cpp float`

Prototype: `#!cpp float abs(float x)`

Parameters:

1.  `#!cpp float x`: The number to find the absolute value of

Returns the absolute value (magnitude) of the given number.

### 4.2. acos

Returning Type: `#!cpp float`

Prototype: `#!cpp float acos(float x)`

Parameters:

1.  `#!cpp float x`: The value to find the inverse cosine of

Returns the inverse cosine (arccos) of the given value

### 4.3. asin

Returning Type: `#!cpp float`

Prototype: `#!cpp float asin(float x)`

Parameters:

1.  `#!cpp float x`: The value to find the inverse sine of

Returns the inverse sine (arcsin) of the given value

### 4.4. atan

Returning Type: `#!cpp float`

Prototype: `#!cpp float atan(float x)`

Parameters:

1.  `#!cpp float x`: The value to find the inverse tangent of

Returns the inverse tangent (arctan) of the given value

### 4.5. atan2

Returning Type: `#!cpp float`

Prototype: `#!cpp float atan2(float x)`

Parameters:

1.  `#!cpp float x`: The X coordinate of the point to find the amplitude of

This is supposed to be the atan2(y, x) function but apparently it only takes one input. ThxDE

### 4.6. cos

Returning Type: `#!cpp float`

Prototype: `#!cpp float cos(float x)`

Parameters:

1.  `#!cpp float x`: The angle (in radians) to find the cosine of

Returns the cosine of the angle in radians

### 4.7. pow

Returning Type: `#!cpp float`

Prototype: `#!cpp float pow(float x, float y)`

Parameters:

1.  `#!cpp float x`: The base value
2.  `#!cpp float y`: The exponenet to raise the base value to

Returns x raised to the power y (x**y).

### 4.8. sin

Returning Type: `#!cpp float`

Prototype: `#!cpp float sin(float x)`

Parameters:

1.  `#!cpp float x`: The angle (in radians) to find the sine of

Returns the sine of the angle in radians.

### 4.9. sqrt

Returning Type: `#!cpp float`

Prototype: `#!cpp float sqrt(float x)`

Parameters:

1.  `#!cpp float x`: The number to find the square root of

Returns the square root of the given number.

### 4.10. tan

Returning Type: `#!cpp float`

Prototype: `#!cpp float tan(float x)`

Parameters:

1.  `#!cpp float x`: The angle (in radians) to find the tangent of

Returns the tangent of the angle in radians

## 5. General

### 5.1. xsChatData

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsChatData(string message, int value)`

Parameters:

1.  `#!cpp string message`: The message to display in chat
2. (Optional) `#!cpp int value`: This value is inserted in place of any `%d` used in the message of the function

Shows the given message in the game chat

### 5.2. xsEffectAmount

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsEffectAmount(int effectID, int unitOrTechnologyID, int attribtueOrOperation, float value, int playerNumber)`

Parameters:

1.  `#!cpp int effectID`: The ID of the effect to use
2.  `#!cpp int unitOrTechnologyID`: The ID of the unit or technology to effect
3.  `#!cpp int attribtueOrOperation`: The attribute to modify or the operation to perform
4.  `#!cpp float value`: The value of the effect
5. (Optional) `#!cpp int playerNumber`: The player to apply the effect to. If unspecified, applies to all players except Gaia.

Change the specified attribute of the specified unit or technology by the value for the specified player. For more information on this, check the [UserPatch]("Jump to: UserPatch NON EXISTENT") section of the guide

### 5.3. xsGetGameTime

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetGameTime()`


Returns the current game time in seconds

### 5.4. xsGetMapHeight

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetMapHeight()`


Returns the Height of the map.

### 5.5. xsGetMapID

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetMapID()`


Returns the AI map type.

### 5.6. xsGetMapName

Returning Type: `#!cpp string`

Prototype: `#!cpp string xsGetMapName(bool showFileExtension)`

Parameters:

1.  `#!cpp bool showFileExtension`: If this is set to true, then the returned name also contains the file extension

Returns the name of the map currently being played.

### 5.7. xsGetMapWidth

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetMapWidth()`


Returns the Width of the map.

### 5.8. xsGetNumPlayers

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetNumPlayers()`


Returns the number of players in the game

### 5.9. xsGetPlayerCivilization

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetPlayerCivilization(int playerNumber)`

Parameters:

1.  `#!cpp int playerNumber`: The player to get the civilization of

Returns the civilization ID of the given player. Refer to the [Constant Reference](../constants/#3-civs "Jump to: XS Scriptin > Constant Reference > #3. Civs") for all the different civ IDs

### 5.10. xsGetPlayerInGame

Returning Type: `#!cpp bool`

Prototype: `#!cpp bool xsGetPlayerInGame(int playerNumber)`

Parameters:

1.  `#!cpp int playerNumber`: Check if this player is still alive

Returns true if the player given is still alive, and false otherwise.

### 5.11. xsGetPlayerNumberOfTechs

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetPlayerNumberOfTechs(int playerNumber)`

Parameters:

1.  `#!cpp int playerNumber`: The player whoes technology count is being requested.

Returns the number of technologies available to the player in the entire game.

### 5.12. xsGetRandomNumber

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetRandomNumber()`


Returns a random number between 0 and 32766.

### 5.13. xsGetRandomNumberLH

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetRandomNumberLH(int low, int high)`

Parameters:

1.  `#!cpp int low`: The lower bound for the range for the random number returned (included)
2.  `#!cpp int high`: The upper bound for the range for the random number returned (excluded)

Returns a random number between `low` and `high`

### 5.14. xsGetRandomNumberMax

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetRandomNumberMax(int max)`

Parameters:

1.  `#!cpp int max`: The upper bound for the range for the random number returned (excluded)

Returns a random number between 0 and `max`.

### 5.15. xsGetTime

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetTime()`


Returns the current game time - 1 in seconds

### 5.16. xsGetVictoryPlayer

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetVictoryPlayer()`


Returns the number of the player with the highest score in a normal game. Returns the number of the player who owns 5 relics or has a wonder if standard victory is enabled. In a game like KoTH, returns the number of the player who owns the monument.

### 5.17. xsGetVictoryTime

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetVictoryTime()`


For game modes like KoTH and other game modes where there is a timer on the screen, it returns the amount of time left in half seconds. meaning if the value returned is 799, it means there are 399.5s remaining

### 5.18. xsGetVictoryType

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetVictoryType()`


Returns an integer corresponding to different victory settings ingame. These are:

 0: Standard

1: Consquest

2: Time Limit

3: Score

4: Custom (scenarios only).

Last Man Standing returns 0 as well.

### 5.19. xsPlayerAttribute

Returning Type: `#!cpp float`

Prototype: `#!cpp float xsPlayerAttribute(int playerNumber, int resourceID)`

Parameters:

1.  `#!cpp int playerNumber`: The player to get the resource of (0 for Gaia)
2.  `#!cpp int resourceID`: The ID of the resource to get the amount of

Returns the amount the specified resource of the given player.

### 5.20. xsResearchTechnology

Returning Type: `#!cpp bool`

Prototype: `#!cpp bool xsResearchTechnology(int techID, bool force, bool techAvailable, int playerNumber)`

Parameters:

1.  `#!cpp int techID`: The technology ID to research.
2.  `#!cpp bool force`: Force researching the tech even if it is not enabled. To force an unavailable tech, the argument `techAvailable` must be set to false
3.  `#!cpp bool techAvailable`: This flag determines if it is required to check if a tech is available before researching it
4.  `#!cpp int playerNumber`: The player to research the technology for

Returns a boolean based on whether the technology was researched or not.

### 5.21. xsSetPlayerAttribute

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsSetPlayerAttribute(int playerNumber, int resourceID, float value)`

Parameters:

1.  `#!cpp int playerNumber`: The player to set the resource of (0 for Gaia)
2.  `#!cpp int resourceID`: The ID of the resource to set the amount of
3.  `#!cpp float value`: The amount to set the resource to

Sets the amount of the specified resource of the given player to the provided value.

### 5.22. xsSetTriggerVariable

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsSetTriggerVariable(int variableID, int value)`

Parameters:

1.  `#!cpp int variableID`: The ID of the variable to set the value of
2.  `#!cpp int value`: The value to set the variable to

Sets the value of the variable of the given variable ID to the provided value.

### 5.23. xsTriggerVariable

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsTriggerVariable(int variableID)`

Parameters:

1.  `#!cpp int variableID`: The ID of the variable to get the value of

Returns the value of the variable of the given variable ID.

## 6. Functions With Seemingly No Practical Use

### 6.1. xsAddRuntimeEvent

Returning Type: `#!cpp bool`

Prototype: `#!cpp bool xsAddRuntimeEvent(string runtimeName, string functionName, int functionArgument)`

Parameters:

1.  `#!cpp string runtimeName`: This is the name of the runtime to create the event in. This should be `"Random Map"` for RMS and `"Scenario Triggers"` for scenarios. Find which one to use in a general script by using the `#!cpp xsGetMapName(true)` [function](./#56-xsgetmapname "Jump To: Function Reference > xsGetMapName") and checking the extension.
2.  `#!cpp string functionName`: This is the name of a user defined function that takes a single integer argument
3.  `#!cpp int functionArgument`: This is an integer argument that is passed to the function given to the argument `functionName` when this event runs.

A runtime event is called after all the XS code has finished executing but before rules start executing. It calls the function `functionName` given to it with the `functionArgument` passed to it as a parameter. For programmers familiar with the terminology, this is basically a way to set a callback. It also returns true if the function name given to it exists, otherwise it returns false. Does not work with built-ins

### 6.2. xsBreakPoint

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsBreakPoint()`


This function adds a break point to the execution of code. Do not use this function and beware, if you do, it will likely cause a crash!

### 6.3. xsDumpArrays

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsDumpArrays()`


This function is supposed to blogs out all XS arrays. Currently, it does absolutely nothing.

### 6.4. xsGetContextPlayer

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetContextPlayer()`


Returns the current context player ID.

### 6.5. xsGetFuntionID

Returning Type: `#!cpp int`

Prototype: `#!cpp int xsGetFuntionID(string functionName)`

Parameters:

1.  `#!cpp string functionName`: The name of the function to get the hash of

Returns the hash of a given function. This function has no practical application and is probably for internal usage only.

### 6.6. xsSetContextPlayer

Returning Type: `#!cpp void`

Prototype: `#!cpp void xsSetContextPlayer(int playerNumber)`

Parameters:

1.  `#!cpp int playerNumber`: The player to set the context player to

In other functions involving a `playerNumber` argument, the value of the context player is used if `-1` is passed as `playerNumber` to them. `xsEffectAmount` will use the value of the context player as its player if `-2` is passed to it as the player argument.

