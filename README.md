# MAL-006: XML External Entity in "Try It" in WSO2 ESB

An error-based XML External Entity (XXE) attack was identified in the WSO2 ESB "Try It" tool.

### Why no CVE?

The vendor replied that "Try it is recommended to be disabled in production" and no public disclosure was made.

### Requirements:

This vulnerability requires:
<br/>
- Valid user credentials
<br/>     OR
- Modify the XML files from a legitimate WSO2 repository
<br/>     OR
- Intercept and modify the files sent to the "Try It" tool

### Proof Of Concept:

More details and the exploitation process can be found in this [PDF](https://github.com/mbadanoiu/MAL-006/blob/main/WSO2%20ESB%20-%20MAL-006.pdf).

