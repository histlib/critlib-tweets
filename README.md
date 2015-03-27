# critlib-tweets
I've used Ed Summers' [twarc](https://github.com/edsu/twarc) to collect [#critlib](https://twitter.com/hashtag/critlib?src=hash) tweets. twarc generates a JSON file, which I then convert to CSV using twarc's json2csv script. Files are named with the date when I grabbed the tweets; twarc grabs a week's worth of content at a time.

March 27, 2015: I've added in the JSON and CSV for the [#critlib15](https://twitter.com/hashtag/critlib15?src=hash) unconference held at ACRL 2015 in Portland, OR. I ran twarc around 10pm on Thursday, March 26. twarc had some problems and was repeatedly capturing a single tweet hundreds of times, so I've edited the JSON and the CSV files to remove the 400 or so repeated tweets.
