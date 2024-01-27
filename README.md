# 3commas-Assist
Node.js code to manipulate 3commas bots and deals to maximise performance.
enter a control code into your bot name, for example "BTC Longbot STP(1.25)" will activate the TP boost based on safety order depth.


// 3 Commas bot assistant, Seeking alpha!
// Check each DCA deal and manipulate various values such as the take profit level based on the depth of the safety orders.
// proposed control codes to be implemented during development.....
// DTP() - Dynamic tp boost on the deal based on some TBD market condition                              (Nope!)
// DSO() - Dynamic S.O. step scale on the bot based on some TBD market condition                        (Nope!)
// TSO() - Trailing Safety orders, helps with trending markets?                                         (Nope!)
// STP() - scaled tp/trail boost on the deal based on SO count*modifier                                 (Fully Working)
// SL(,) - apply +ve stop loss on deal at specified point (%pnl,S.O. depth)                             (MOSTLY WORKING, NEED HELP TSL bugged at 3c)
// SPAWN() 	- allow additional deal only if safe (green stop loss or TTP is active )                    (Fully Working)
// WATCH() - Monitor Margin ratio to prevent SPAWN or anything else getting out of hand, cancel SO's ? 	(Nope)
// CONV()  	- lock SL & smart trade convert only if a Stop loss or TTP is set                           (WIP NOW, works) 
// SWAPCOIN()- swap in hotest/safest trading pairs from lunar crush or similar RSS feed/api            	(Nope!)
// BLKLST()	 - update blacklist with bad pairs, recent pumps etc (independant of bot/deal) every hour ?	(Nope!)  
// Exclude any deals marked with the user notes text from being modified                                (PARTIALLY IMPLEMENTED) 
.


