# LiquidFun.js

A professional, developer friendly, native JavaScript optimized Box2D and LiquidFun library.
Not an unreadable ASM.js result of c++ cross compliation.

Box2d fully documented with Erin Catto's original comments, LiquidFun fully documented with the Google teams original
comments for easier developer education and all round ENJOYABLE experience.

YUIdoc syntax comments to generated API website to not only slash the learning curve, but to also add 'type' compatibility 
for Google Closure Compiler, which compiles source code into excellent JavaScript optimisations and deployment compression.

Light weight and optimized for web. Containing all the Joints and functionality of Box2D v2.3.1 but with an API closer 
to Box2D v2.1a to reduce the non-essential later added Box2D convenience methods. All prototype chain lookups 
slashed to minimum. 'Scope' and 'context' are managed by the call stack instead of the commonly used and more expensive 
Function object convenience methods .apply() and .call() which are not used. All classes are written in their own file 
(for enjoyable source code management) and COMPATIBLE with Google Closure Compiler. But NOT utilising the non-essential
goog.provides()/imports(). Classes are manually sequenced, to eliminate 100's of those 'goog' calls and also the need to
include Closure library's 'base.js' which combined just add unnecessary extra work for the browser and bloat the deployed
library.

Plans to possibly replace LinkedList data structures c++ requires for memory management with more efficient LookupTable data
Structures. LookupTables are apparently more compatible with the JavaScript environment than they were with c++ environment.
