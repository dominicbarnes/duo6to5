
duo-6to5
========

duo plugin for [sebmck/6to5](https://github.com/sebmck/6to5).


Installation
------------

    $ npm install duo-6to5


Usage
-----

From the CLI:

    $ duo --use duo-6to5

Using the API:

```javascript
Duo(root)
  .entry(entry)
  .use(to5)
  .run(fn);
```


API
---

__to5([opts])__
Initialize a duo plugin. `opts` are passed directly into 6to5.


License
-------

The MIT License

Copyright (C) 2014 BDO a.s &lt;labs@bdo.no&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE
OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

