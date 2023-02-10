## XRAY 16 Engine Modifications
## Open X-Ray Call of Chernobyl Edition
----
This repository contains XRAY Engine sources based on version 1.6.02 for specific use with the Call of Chernobyl modification.
The original engine is used in S.T.A.L.K.E.R. Call of Pripyat game released by GSC Game World and any changes to this engine are allowed for ***non-commercial*** use only (see [License.txt](https://github.com/avoitishin/xray-16/blob/master/License.txt) for details).

**Note** that [Master](https://github.com/revolucas/xray-16/tree/master) branch contains stable code that is documented on [Wiki](https://github.com/revolucas/xray-16/wiki) but you can also checkout [Working](https://github.com/revolucas/xray-16/tree/working) for nightly builds

* Build instructions can be found [here](https://github.com/avoitishin/xray-16/wiki/Build-Instructions)
* If you find a bug or have an enhancement request, file an [Issue](https://github.com/revolucas/xray-16/issues).
* Please go to our [Wiki](https://github.com/avoitishin/xray-16/wiki) pages for detailed description of changes and other useful information.   

  
---
Pull requests appreciated! Just check out 
[the task list](https://github.com/revolucas/xray-16/blob/master/doc/design/task_list.txt) 
and follow our [procedures](https://github.com/revolucas/xray-16/tree/master/doc/procedure). (**not** updated for this code base yet)

I got the code here:
https://bitbucket.org/SeargeDP/coc-1.4-xray-64/src/coc-1.4-xray-64/

and modified it to compile out of the box on Release x64 on the Express 2013 edition of Visual Studio (The code is C++ 11) and later versions do not support this (2019+)
and this presents a huge issue with the amount of overloaded classes and other code that currently is not compatible with VS2022.

any help is appreciated.