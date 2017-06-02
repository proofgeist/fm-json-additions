##JSON.ArrayConcat ( firstArray;secondArray)```/**
 * =====================================
 * JSON.ArrayConcat ( firstArray ; secondArray )
 *
 * RETURNS:
 *	a longer array of the first & second concatinated
 *
 * PARAMETERS:
 *	firstArray 
 *	secondArray 
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
 *	Created, 2017-05-07, cdelfs@delfsengineering.ca
 *
 * =====================================
 */```##JSON.ArrayFromRelated ( JSONField)```/**
 * =====================================
 * JSON.ArrayFromRelated( JSONField )
 *
 * RETURNS:
 *	an array containng the values from the related field
 *
 * PARAMETERS:
 *	JSONField 
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
 *	Created, 2017-06-01, todd@geistinteractive.com
 *
 * =====================================
 */```##JSON.ArrayLength ( array;path)```/*
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
 */```##JSON.ContainsProperty ( json;name)```/**
 * =====================================
 * JSONContainsProperty ( array ; path )
 *
 * RETURNS:
 *	an array containing only the values that pass the test
 *
 * PARAMETERS:
 *	json = a valid JSON object
 *	name = the property to test (can be in form body.path.item)
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
 * 	Amended, 2017-05-16, john@e-rwu.com, added path depth, gh #3
 *	Created, 2017-04-09, todd@geistinteractive.com
 *
 * =====================================
 */```##JSON.FilterByExpression ( array;expression)```/**
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
 */```##JSON.GetValuesAtPath ( array;path)```/**
 * =====================================
 * JSONGetValuesAtPath ( array ; path)
 *
 * RETURNS:
 *	a list containing only the values at that path
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
 *	Amended, 2017-05-16, john@e-rwu.com, fixes gh #5, #4
 *	Created, 2017-04-01, todd@geistinteractive.com
 *
 * =====================================
 */```##JSON.Merge ( target;source)```/**
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
 *	FIXED Bug # 1 on 2017–May 15 Todd Geist, todd@geistinteractive.com
 *	CREATED on 2017-APR-04 Todd Geist, todd@geistinteractive.com
 *
 * =====================================
 */```