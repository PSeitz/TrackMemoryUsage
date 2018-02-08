# TrackMemoryUsage
Tracks memory usage of process every 5 seconds in the format:

|Size	|Resid.	|Shared	|Data	|%
| --- | --- | --- | --- | --- |
|1215236	|219467	|15734	|747143	|0.9
1215236	|219467	|15734	|747143	|0.9

`curl -L https://raw.githubusercontent.com/PSeitz/TrackMemoryUsage/master/memusage.sh | bash /dev/stdin processname`
