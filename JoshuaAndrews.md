# Vulnerability Taxonomy CWE Homework

The CPE I found in my personal code is as follows.


`cpe:2.3:a:JoshuaAndrews:Trie.cpp:1.0.0:1:en-us:GCC-6.3.0:*:*:*:`

~~~~~~~~~

  The CPE that I generated from my found personal CVE refers to version 2.3 of the Common Platform Enumerations. The CPE shows this was an application that was made by me and goes by the product name of Trie.cpp. Additionally, this was the first "released" version and edition of the application, made for american english usage. Finally, the software this was made on the latest version of c++. This CVE was found in an alphabet trie I made recently. Each node in the Trie has a vector of pointers that refer to the next node in the trie. Early versions of this application were able to write past the array on certain endge case conditions which cased a lot of data from the Trie and potential security risks in the actual application.

~~~~~~~~~~
  This CVE is a perfect example of my chosen CWE which "CWE-787: Out-of-bounds Write". The application was able to write data past the alloted buffer of the pointer vector that is being written to. An obvious corruption of expected data is caused by the vector not string the data being written as well as storage used elsewhere on the system being overwritten by a value that is not expected or handled. Some other examples of this CWE include,
  
`CVE-2021-28664: https://www.cve.org/CVERecord?id=CVE-2021-28664`


`CVE-2020-0041: https://www.cve.org/CVERecord?id=CVE-2020-0041`


`CVE-2021-21220: https://www.cve.org/CVERecord?id=CVE-2021-21220`  
