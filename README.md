# fm-virtual-list


# Dependencies:
* Custom Functions:
	Error
	Error.Description
	Error.IsError
	Error.Last
	Result

# Installation
1. Import VirtualList table
2. Impot VirtualList script folder

# Usage
* The data should be formatted as an array of arrays:
	[
		[datum1,datum2,datum3,...],
		[datum1,datum2,datum3,...],
		...
	]
* The metadata should be formatted as an array of objects. The objects can contain whatever keys you want. Some common keys would be "id", "table", "type".
* To parse the data into variable repetitions that the VL table can read, send both arrays as properties of the script parameter to the script `CreateVL Variables From Array`.
* To clear the variable repetitions call `Clear VL Variables`
