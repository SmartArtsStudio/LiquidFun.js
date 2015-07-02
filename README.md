# LiquidFun.js

A professional, developer friendly, native JavaScript optimized Box2D and LiquidFun library. 
Not an unreadable ASM.js result of c++ cross compliation.
Box2d fully documented with Erin Catto's original comments, LiquidFun fully documented with the Google teams original
comments for easier developer education and all around ENJOYABLE experience.

YUIdocs comments to generated API website to not only slash the learning curve, but to also add compatibility with
Google Closure Compiler for excellent deployment compression.

Light weight and optimized for web: Containing all the Joints and functionality of Box2D v2.3.1 but with an API closer 
to Box2D v2.1a to reduce the unnecessary overhead of later added Box2D convenience methods. All prototype chain lookups 
slashed to minimum. 'Scope' and 'context' are managed by the call stack instead of the commonly used and more expensive 
JavaScript Function object's convenience methods .apply() and .call() (not used or needed).

Plans to possibly replace LinkedList data structures c++ requires for memory management with more efficient LookupTable data
Structures. LookupTables are apparently more compatible with the JavaScript environment than they were with c++ environment.
