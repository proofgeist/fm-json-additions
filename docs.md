##JSON.ArrayConcat ( firstArray;secondArray)```/**
 *
 * concatinates two arrays
 *
 * @param {array} firstArray
 * @param {array} secondArray
 *
 * @returns {array}
 * 
 * @package JSON - Extensions to the Native JSON Functions
 *
 * @author cdelfs@delfsengineering.ca
 * @version 20170507
 *
 */```##JSON.ArrayFromRelated ( JSONField)```/**
 *
 * builds an array from a related field
 *
 * @param {*} the related field
 *
 * @returns {array}
 * 
 * @package JSON - Extensions to the Native JSON Functions
 *
 * @author todd@geistinteractive.com
 * @version 20170601
 *
 */```##JSON.ArrayLength ( array;path)```/**
 *
 * gets the length of the array
 *
 * @param {*} array or object to get the length
 * @param {string} the path to target the array
 *
 * @returns {number}
 * 
 * @package JSON - Extensions to the Native JSON Functions
 *
 * @author todd@geistinteractive.com
 * @version 20170409
 *
 */```##JSON.ContainsProperty ( json;name)```/**
 *
 * returns true if the JSON Object contains a given property
 *
 * @param {object} json
 * @param {string} property to test for, or path.
 *
 * @returns {boolean} 0 or 1
 * 
 * @package JSON - Extensions to the Native JSON Functions
 *
 * @author todd@geistinteractive.com
 * @version 20170516
 *
 */```##JSON.FilterByExpression ( array;expression)```/**
 *
 * filters the array with a FileMaker expression
 *
 * @param {array} array the array to filter
 * @param {string} expression the FileMaker expression to use for the filter
 *
 * @returns {array}
 * 
 * @package JSON - Extensions to the Native JSON Functions
 *
 * @author todd@geistinteractive.com
 * @version 20170401
 *
 */```##JSON.GetValuesAtPath ( array;path)```/**
 *
 * gets a list of values from the path
 *
 * @param {array} array
 * @param {string} path or property
 *
 * @returns {string} list of the values
 * 
 * @package JSON - Extensions to the Native JSON Functions
 *
 * @author todd@geistinteractive.com
 * @version 20170516
 *
 */```##JSON.Merge ( target;source)```/**
 *
 * merges two json objects together
 *
 * @param {object} target the object to merge into
 * @param {object} source the object to merge properties for
 *
 * @returns {object}
 * 
 * @package JSON - Extensions to the Native JSON Functions
 *
 * @author todd@geistinteractive.com
 * @version 20170516
 *
 */```