# fmp4-ingest

Initial fMP4 ingest Requirements 
1.	fMP4 ingest shall standardize a transport protocol for live media source ingest
2.	fMP4 ingest shall support push based transmission of live stream events
3.	fMP4 ingest shall support timed meta data such as based on ID3 and SCTE-35
4.	fMP4 ingest specification shall support ingest of MPEG-H and MPEG-4 media including HEVC, AVC, AAC, MPEG-H audio and other media formats
5.	fMP4 ingest media ingest shall be based on media fragments (moof box and mdat) as specified by ISOBMFF
6.	fMP4 ingest shall use clock synchronization between streams, preferably on UTC timestamps form the original (e.g. SDI) signal
7.	fMP4 ingest shall be based on MPEG technologies and container formats 
8.	fMP4 ingest spec shall specify failover and restart procedures to gracefully restart in case of failovers
9.	fMP4 ingest spec document shall specify best practices for media source redundancy and service redundancy (i.e. continuation of the live event after failure of media source or service node)
10.	fMP4 ingest specification shall support graceful teardown of ingest of live stream events
11.	fMP4 ingest shall use HTTP Post for media source ingest
12.	fMP4 ingest shall support low latency media source ingest
13. fMP4 ingest shall be supported by an openly available reference implementation ????
