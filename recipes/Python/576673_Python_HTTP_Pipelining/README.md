## Python HTTP PipeliningOriginally published: 2009-02-27 16:14:13 
Last updated: 2009-02-27 16:21:23 
Author: Markus J 
 
Gets several pages in parallel, without threads. It exploits HTTP pipelining by resetting the state of HTTPConnection to trick it into sending the next request ahead of time.