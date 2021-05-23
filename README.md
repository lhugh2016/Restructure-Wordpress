# Restructure-Wordpress
Develop a pseudo compiler to navigate through Wordpress system, and restructure its system and directories so that Wordpress system may become easier for beginners.

At the first step, a "token analyzer" has been developed to process some small set of words, such as "define", "global", "require", "require_once", "include". Using it, the code can trace file links from one file to another and produce an index of the hierarchy.
A total of about 6431 files in the Wordpress system have been indexed. 

Further work will refine the set of tokens to include "if" to further differentiate the running paths in the Wordpress depending on client's http request.
