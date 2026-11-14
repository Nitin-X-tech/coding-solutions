# OFFICE - Rating 519

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-14T18:04:16.214Z  

```c_cpp
#include <stdio.h>

int main() {
	// your code goes here
	int t,x,y,z;
	scanf("%d",&t);
	while(t--){
	    scanf("%d%d%d",&x,&y,&z);
	    if(z>(x*y/2))
	    {
	    printf("yes");
	    } else
	   { printf("no");
	   }
	    printf("\n");
	}

}


```

---

[View on CodeChef](https://www.codechef.com/problems/OFFICE)