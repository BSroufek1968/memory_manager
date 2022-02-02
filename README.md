# memory_manager
Memory Manager operates with a Mmalloc, Mfree and Mrealloc interface

void    *MMEMgetVirt(int blockSize); 
and
int     MMEMfreeVirt(void *chunkPtr);

can be modified to attach to a specific memory location.
