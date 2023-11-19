# 3commas-Assist
Node.js code to manipulate 3commas bots and deals to maximise performance.


// 3 Commas bot assistant, Seeking alpha!

// Check each DCA deal and manipulate various values like take profit level based on the depth of the safety orders.

// proposed control codes to be implemented during development.....

// DTP() - Dynamic tp boost on the deal based on some TBD market condition      (Nope!)

// DSO() - Dynamic S.O. step scale on the bot based on some TBD market condition(Nope!)

// STP() - scaled tp boost on the deal based on SO count*modifier               (NOW FULLY WORKING)

// SL(,) - apply +ve stop loss on deal at specified point (%pnl,S.O. depth)     (Nope, 3rd party API has missing implementation!)

// SPAWN(,) 	- allow additional deal or smart trade convert after (%pnl,S.O. depth) only if a Stop loss or TTP is set (Nope!) 

// SWAPCOIN()	- swap in hotest/safest trading pairs from lunar crush or similar RSS feed/api (Nope!)

// BLKLST()		- update blacklist with bad pairs, recent pumps etc (independant of bot/deal) every hour ? (Nope!) 

// Exclude any deals marked with the user notes text from being modified        (PARTIALLY IMPLEMENTED)


