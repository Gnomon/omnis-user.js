# omnis-user.js

add user.js into your jsctempl.htm 
after the Omnis Studio JavaScript client scripts 
to give the jsclient additional functions


<!-- Omnis Studio JavaScript client scripts -->
<script type="text/javascript" src="scripts/811/ssz.js"></script>
<script type="text/javascript" src="scripts/811/omjsclnt.js"></script>
<script type="text/javascript" src="scripts/811/omjqclnt.js"></script>


<!-- Edit user.js to enhance the jsclient with your functions-->
<script type="text/javascript" src="scripts/user.js"></script>


Enhancements 20170106

enhancements: 
- simple functions like right() as demo how to add your own functions
- function provide_headerfiles: tries to dynamically load css files needed
- function copy2localList: allows smartlists to be copied into local lists
- function lstData2lstDataObj: convert a list into an object usable e.g. for the marquee library
- function lstData4Sync: convert a list into a nicely transferable object 
- function colData extracts a column out of a list
- function $fullname: gives a more omnis like notation for an object
- function $registerInNotation: supports remoteObjects and clientdbs
- function $registerMethos: simplifies notational access

bugfixes:
- function methodExists: more reliable with messed up old forms
