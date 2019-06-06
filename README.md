# dc-nbd
Server side support for dc.js with NativeBigData server

dc.js (https://dc-js.github.io/dc.js/) is a javascript charting library with native crossfilter support, allowing highly efficient exploration on large multi-dimensional datasets (inspired by crossfilter's demo). It leverages d3 to render charts in CSS-friendly SVG format. Charts rendered using dc.js are data driven and reactive and therefore provide instant feedback to user interaction. 

Native Big Data (https://nativebigadata.com/) is a software that lets run Big Data algorithms in a cluster of computers. Current Big Data platforms are not implemented in native languages. This means that the used hardware will wast a lot of resources (time, energy, money) doing useless tasks (translating tons of bytecodes). Software running on a computer natively means that it will run without any external support as contrasted to running in emulation. Software implemented in a native language like C runs faster  with less resources. In general, programs made in C runs 2-20 times faster than programs made in other technologies (Java, C#, Scala, ...).
Native Big Data is 100% implemented in C.

dc-js works with a great performance in browsers when the volume of data and the number of charts are not so big. In a Big Data scenario dc.js can't execute algorithms in a browser and the power of a server or a net of servers is needed. In this scenario NBD (nativebigdata) is the best platform to solve this problem.

