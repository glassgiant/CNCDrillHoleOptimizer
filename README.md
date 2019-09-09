# CNCDrillHoleOptimizer
//by Shawn Wilson Sept 2019
//
//Takes a JS array of X/Y coords and does a rough optimization on them to reduce travel time for CNC milling a bunch of drill operations.
//Spits the original travel distance and optimized travel distance out to console.
//Originally designed to optimize CNC milling cribbage boards (361 holes)
//displays original path in GRAY, optimized in YELLOW
//Start hole is GREEN.  Last hole is RED.

//FUTURE FEATURE POSSIBILITIES
//calculate the multiplier automatically
//remove the hard-coded values for GCode options (safety height, feed rate, etc.) and Canvas colors, stroke widths, etc.
//Make the HTML/CSS more MVC
