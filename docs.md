## JSON.ArrayConcat ( firstArray;secondArray)
```
/**
 * 
 * JSON.ArrayConcat ( firstArray ; secondArray )
 *
 * RETURNS:
 *	a longer array of the first & second concatinated
 *
 * @param {array} firstArray
 * @param {array} secondArray
 *
 * @returns {array}
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 * 
 * @history 2017-05-07, cdelfs@delfsengineering.ca
 *
 */
```
## JSON.ArrayFromRelated ( JSONField)
```
/**
 * 
 * JSON.ArrayFromRelated( JSONField )
 *
 *@params {reference} JSONField a reference to the field
 *
 *@returns {array} array containng the values from the related field
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 * 
 * @history 2017-06-01, todd@geistinteractive.com, created
 *
 */
```
## JSON.ArrayLength ( array;path)
```
/*
 * 
 * JSONArrayLength ( array ; path)
 *
 * @param {array} array a valid JSON Array
 * @param {string} path the path to the array if it is nested
 *
 * @returns {number}
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 * 
 * @history 2017-04-09, todd@geistinteractive.com, created
 *
 * =====================================
 */
```
## JSON.ArraySort ( array;sortChildren)
```
/**
 * 
 * Sort an array
 *
 * @param {array} array a valid JSON array
 * @param {string} sortChildren
 *
 * @returns {array} 
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 * 
 * @history  2017-06-20, michael.wallace@rcconsulting.com , gh #12
 *
 */
```
## JSON.ContainsProperty ( json;name)
```
/**
 * =====================================
 * 
 * Test if the JSON contains the give property
 *
 * @param {object} json a valid JSON object
 * @param {string} name the property to test (can be in form body.path.item)
 *
 * @returns {boolean} 
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 * 
 * @history 2017-10-12, todd@geistinteractive.com, fixed depth gh #14
 * @history  2017-05-16, john@e-rwu.com, added path depth, gh #3
 * @history  2017-04-09, todd@geistinteractive.com
 *
 * =====================================
 */
```
## JSON.FilterByExpression ( array;expression)
```
/**
 *
 * filters the array by a FileMaker expression
 *
 *@param {array} array a valid JSON Array
 *@param {string} expression a valid FileMaker Expression. 
 *				It can use 
 *				"$item" to access the array item for use
 *				in the filter calculation.
 *
 * @returns {array} 
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 * 
 * @history, 2017-06-20, michael.wallace@rcconsulting.com
 * @history 2017-04-01, todd@geistinteractive.com
 *
 */
```
## JSON.Format ( text;descriptor)
```
/**
 *
 * Formats the JSON for readability and
 * checks if it is valid.
 * designed for the start of scripts
 *
 * @param {string} text the string to to test
 * @param {string} descriptor the error descriptor to use if there is one.
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 *
 * @history 2017–11-24 created, todd@geistinteractive.com
 *
 */
```
## JSON.GetValuesAtPath ( array;path)
```
/**
 * 
 * returns list containing only the values at that path
 *
 * @param {array} array a valid JSON Array of objects
 * @param {string} the path to the property you want to list
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 * 
 * @history 2017-05-16, john@e-rwu.com, fixes gh #5, #4
 * @history 2017-04-01, todd@geistinteractive.com, created
 *
 * =====================================
 */
```
## JSON.IsValid ( json)
```
/**
 *
 * Tests to see if the JSON object is valid
 *
 * @param {object} json the JSON object to to test

 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 *
 * @history 2017–11-29 updated doc block for clarity, dave@geistinteractive.com
 * @history 2017–11-23 created, todd@geistinteractive.com
 *
 */
```
## JSON.Merge ( target;source)
```
/**
 *
 * performs a shallow merge on two JSONObjects
 *
 * @param {object} target the object to merge into
 * @param {object} source the object to merge from
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 *
 * @history 2017–05-15 fixed gh# 1, todd@geistinteractive.com
 * @history 2017–04-04 created, todd@geistinteractive.com
 *
 */
```
## JSON.Pluck ( PluckList)
```
/**
 * =====================================
 *
 * Applies a list of JSON.PluckProps. to a $JSON.Pluck.From
 *
 * @param {list} PluckList the list of Plucks to apply
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 *
 * @history 2017-09-01 created, todd@geistinteractive.com
 *
 * =====================================
*/
```
## JSON.Pluck.From ( JSON)
```
/**
 * =====================================
 *
 *  helper function that store the source json to a known var 
 *  $JSON.Pluck.From
 *
 * @param {object} the json to Pluck from
 * 
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 *
 * @history 2017-09-01 created, todd@geistinteractive.com
 *
*/
```
## JSON.Pluck.Prop ( PropToPluck;JSONType;As)
```
/**
 * =====================================
 *
 * Plucks the prop from the source JSON and puts in the new JSON
 * 
 * @param {string} PropToPluck the name of the prop to pluck from the souce JSON
 * @param {number} [JSONType], JSONType, use the provided constants, defaults to "" which means it will guess
 * @param {string} [As=PropToPluck] an optional name to use instead of the original name defaults to PropToPluck
 *  
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 *
 * @history 2017-09-01 created, todd@geistinteractive.com
 *
 * =====================================
 */
```
## JSON.Push ( target;source;type)
```
/**
 *
 * JSON.Push ( target ; source ; type )
 *
 * Pushes a new object onto the end of the array
 *
 * @param {object} source : the object to push
 * @param {array} target : the array receiving the object
 * @param {constant} type : a valid JSON type constant (e.g., JSONString)
 *
 * @requires {function} JSON.ArrayLength
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 *
 * @history 2017-11-30 dave@geistinteractive.com
 * - Validate target instead of source
 * - Allow for empty target
 * - Added JSON type constant to accept source with all valid JSON elements
 * @history 2017-11-29 created, dave@geistinteractive.com
 *
 */
```
## JSON.Transform ( TransformationList)
```
/**
 * =====================================
 *
 * Applies a list of JSON.Transformation. to $JSON.Pluck.This
 *
 * @param {list} TransformationList the list of Transformations to apply
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 * @history 2017-11-17 created, todd@geistinteractive.com
 *
 * =====================================
*/
```
## JSON.Transform.ISODates ( path;Type)
```
/**
 * =====================================
 *
 * Performs an ISO Date and Time transform on the given property
 * 
 * @param {string} path the path to the value to be transformed
 * @param {string} [Type] A type of transform to apply. Must be one of "Date.ToISO", "Date.FromISO", "Time.FromISO", "Time.ToISO", "TimeStamp.ToISO", "TimeStamp.FromISO", 
 *
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 *
 * @history 2017-11-17 created, todd@geistinteractive.com
 * =====================================
 */
```
## JSON.Transform.This ( JSON)
```
/**
 * =====================================
 *
 *  helper function that store the source json to a known var 
 *  $JSON.Pluck.This
 *
 * @param {object} the json to Transform
 *  
 * @module fm-json-additions
 * @see https://github.com/geistinteractive/fm-json-additions
 * @history 2017-11-17 created, todd@geistinteractive.com
 *
*/
```
