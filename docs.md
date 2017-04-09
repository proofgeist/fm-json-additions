##JSONArrayLength ( array;path)```/**
 * =====================================
 * JSONArrayLength ( array ; path)
 *
 * RETURNS:
 *	an array containing only the values that pass the test
 *
 * PARAMETERS:
 *	array = a valid JSON Array
 *	path = the path to the array if it is nested
 *
 * DEPENDENCIES:
 *	FileMaker 16 or Later
 *
 * NOTES:
 *
 *
 * FAMILY:
 *	JSON - Extensions to the Native JSON Functions
 * 
 * HISTORY:
 *	Created, 2017-04-09, todd@geistinteractive.com
 *
 * =====================================
 */```##JSONContainsProperty ( json;name)```/**
 * =====================================
 * JSONContainsProperty ( array ; path)
 *
 * RETURNS:
 *	an array containing only the values that pass the test
 *
 * PARAMETERS:
 *	json = a valid JSON object
 *	name = the property to test
 *
 * DEPENDENCIES:
 *	FileMaker 16 or Later
 *
 * NOTES:
 *
 *
 * FAMILY:
 *	JSON - Extensions to the Native JSON Functions
 * 
 * HISTORY:
 *	Created, 2017-04-09, todd@geistinteractive.com
 *
 * =====================================
 */```##JSONFilterByExpression ( array;expression)```/**
 * =====================================
 * JSONFilterByExpression ( array ; expression)
 *
 * RETURNS:
 *	an array containing only the values that pass the test
 *
 * PARAMETERS:
 *	array = a valid JSON Array
 *	expression = 	a valid FileMaker Expression. It can use 
 *				"$item" to access the array item for use
 *				in the filter calculation.
 *
 * DEPENDENCIES:
 *	FileMaker 16 or Later
 *
 * NOTES:
 *
 *
 * FAMILY:
 *	JSON - Extensions to the Native JSON Functions
 * 
 * HISTORY:
 *	Created, 2017-04-01, todd@geistinteractive.com
 *
 * =====================================
 */```##JSONGetValuesAtPath ( array;path)```/**
 * =====================================
 * JSONGetValuesAtPath ( array ; path)
 *
 * RETURNS:
 *	an array containing only the values at that path
 *
 * PARAMETERS:
 *	array = a valid JSON Array of objects
 *	path = the path to the property you want to list
 *
 * DEPENDENCIES:
 *	FileMaker 16 or Later
 *
 * NOTES:
 *
 *
 * FAMILY:
 *	JSON - Extensions to the Native JSON Functions
 * 
 * HISTORY:
 *	Created, 2017-04-01, todd@geistinteractive.com
 *
 * =====================================
 */```##JSONMerge ( target;source)```/**
 * =====================================
 * jsonMerge ( target ; source )
 *
 * PURPOSE:
 *	performs a shallow merge on two JSONObjects
 *
 * RETURNS:
 *	the Object
 *
 * PARAMETERS:
 *	target = the object to merge into
 *	source = the object to get properties to merge into the target
 *
 * DEPENDENCIES:
 *	FileMaker 16
 *
 * FAMILY:
 *	JSON - Extensions to the Native JSON Functions
 *
 * HISTORY:
 *	CREATED on 2017-APR-04 Todd Geist, todd@geistinteractive.com
 *
 * =====================================
 */```