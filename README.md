## Implementation of TCP Duplicate Selective Acknowlegement (DSACK) in ns-3.

+ Contributors : Siddhartha Chowdhuri, Atul Singh, Aswin Manoj.
+ Instructor   : Mohit P. Tahiliani.

#### About D-SACK :

+ The Selective Acknowledgement (SACK) option is used by the TCP data receiver to acknowledge non-contiguous blocks of data not covered by the Cumulative Acknowledgement field.

+ When D-SACK is used, the first block of the SACK option should be a D-SACK block specifying the sequence numbers for the duplicate segment that triggered the acknowledgement.

+  The left edge of the D-SACK block specifies the first sequence number of the duplicate contiguous sequence, and the right edge of the D-SACK block specifies the sequence number immediately following the last sequence in the duplicate contiguous sequence.

#### Resources    :

 + RFC 2018 : [TCP Selective Acknowledgment Options.](https://tools.ietf.org/html/rfc2018)
 
 + RFC 2883 : [An Extension to the Selective Acknowledgement (SACK) Option for TCP.](https://tools.ietf.org/html/rfc2883)
 
 
 

