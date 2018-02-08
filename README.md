# TrackMemoryUsage
Tracks memory usage of process every 5 seconds in the format ([Source](https://superuser.com/questions/620004/invoke-and-track-memory-usage-of-one-process?rq=1)):

|Size	|Resid.	|Shared	|Data	|%
| --- | --- | --- | --- | --- |
|1215236	|219467	|15734	|747143	|0.9
1215236	|219467	|15734	|747143	|0.9

`curl -L https://raw.githubusercontent.com/PSeitz/TrackMemoryUsage/master/memusage.sh | bash /dev/stdin processname`

