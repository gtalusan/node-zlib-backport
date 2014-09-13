# Zlib sync methods backported for 0.10.x

Zlib synchronous methods has been pushed to node 0.11.12. This library is based on the official node zlib code from 0.10.31 release. The code has been slightly modified to expose the following methods.

* zlib.deflateSync(buf)
* zlib.deflateRawSync(buf)
* zlib.gzipSync(buf)
* zlib.gunzipSync(buf)
* zlib.inflateSync(buf)
* zlib.inflateRawSync(buf)
* zlib.unzipSync(buf)



### Documentation

You can find project documentation at https://github.com/joyent/node/blob/v0.11.12/doc/api/zlib.markdown

**Pay attention that options argument object and zlib.params have not been backported.**



## License

Copyright Joyent, Inc. and other Node contributors.  
 
Permission is hereby granted, free of charge, to any person obtaining a  
copy of this software and associated documentation files (the  
"Software"), to deal in the Software without restriction, including  
without limitation the rights to use, copy, modify, merge, publish,  
distribute, sublicense, and/or sell copies of the Software, and to permit  
persons to whom the Software is furnished to do so, subject to the  
following conditions:  
 
The above copyright notice and this permission notice shall be included  
in all copies or substantial portions of the Software.  
 
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS  
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF  
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN  
NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,  
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR  
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE  
USE OR OTHER DEALINGS IN THE SOFTWARE.  
  
