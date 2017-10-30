---
title: Identification
weight: 5
---

## Identification

Attribute 		| Type 		| Example 			| Description
--------- 		| ------- 	| ----------- 		|	-----------
stableName 		| string 	| The Deer 			| a name the horse is known by on a day-to-day basis
stableNameAKA 	| string[] | Donnie, Donnerd, Rhonda | additional common names  
uelnID 			| string 	| 25000100155928M	| [universal equine life number](http://inside.fei.org/fei/veterinarians/passports/ueln)
rideAlertID 	| string 	|					| a unique code from [RideAlert](http://www.ridealert.us/)
registryInfo	| registryInfo[]	|					|

```csharp
string BarnName { get; set; }
List<string> BarnNameAKA { get; set; }
string FormalName { get; set; }
```

```objective_c
NSString *barnName;
NSArray<NSString *> *barnNameAKA;
NSString *formalName;
```