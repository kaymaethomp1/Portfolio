---
title: Assignment 1
subtitle: Computer performance, reliability, and scalability calculation
author: Kayla Thompson
---

## 1.2 

#### a. Data Sizes

| Data Item                                  | Size per Item | 
|--------------------------------------------|--------------:|
| 128 character message.                     | 128 Bytes     |                  
| 1024x768 PNG image                         | 0.45 MB       |
| 1024x768 RAW image                         | 1.03 MB       | 
| HD (1080p) HEVC Video (15 minutes)         | 1.08 GB       |
| HD (1080p) Uncompressed Video (15 minutes) | 167.96 GB     |
| 4K UHD HEVC Video (15 minutes)             | 1.52 GB       |
| 4k UHD Uncompressed Video (15 minutes)     | 167.94  GB    |
| Human Genome (Uncompressed)                | 0.75 GB       |

  
sources:
https://web.stanford.edu/class/cs101/bits-bytes.html

https://toolstud.io/photo/megapixel.php?width=1024&height=768&compare=video&calculate=compressed#calculate

https://toolstud.io/photo/megapixel.php?width=1024&height=768&compare=video&calculate=compressed#calculate

https://toolstud.io/video/filesize.php?width=1920&height=1080&framerate=30&timeduration=15&timeduration_unit=minutes&compression=19290&specificbitrate=100&specificbitrate_unit=1000000

https://toolstud.io/video/filesize.php?width=1920&height=1080&framerate=30&timeduration=15&timeduration_unit=minutes&compression=3000000&specificbitrate=100&spe

https://toolstud.io/video/filesize.php?width=1920&height=1080&framerate=30&timeduration=15&timeduration_unit=minutes&compression=27127&specificbitrate=100&specificbitrate_unit=1000000

https://toolstud.io/video/filesize.php?width=1920&height=1080&framerate=30&timeduration=15&timeduration_unit=minutes&compression=27127&specificbitrate=100&specificbitrate_unit=1000000

https://en.wikipedia.org/wiki/Human_genome#Information_content
  

#### b. Scaling

|                                           | Size     | # HD | 
|-------------------------------------------|---------:|-----:|
| Daily Twitter Tweets (Uncompressed)       | 64 GB    |   1  |
| Daily Twitter Tweets (Snappy Compressed)  | 32 GB    |   1  |
| Daily Instagram Photos                    | 253.9  TB| 76.2 | 
| Daily YouTube Videos                      | 7720 TB  | 2316 |
| Yearly Twitter Tweets (Uncompressed)      | 23.73 TB | 7.1  |
| Yearly Twitter Tweets (Snappy Compressed) | 11.87 TB | 3.6  |
| Yearly Instagram Photos                   |92673.5 TB| 27813|
| Yearly YouTube Videos                     |2817800 TB|845340|

source: https://www.infoq.com/news/2011/04/Snappy/

#### c. Reliability
|                                    | # HD | # Failures |
|------------------------------------|-----:|-----------:|
| Twitter Tweets (Uncompressed)      | 7.1  |     0.06   |
| Twitter Tweets (Snappy Compressed) | 3.6  |     0.03   |
| Instagram Photos                   |27813 |    236.4   |
| YouTube Videos                     |845340|   7185.4   |

source: https://www.backblaze.com/b2/hard-drive-test-data.html

#### d. Latency

|                           | One Way Latency      |
|---------------------------|---------------------:|
| Los Angeles to Amsterdam  | 12.48 ms             |
| Low Earth Orbit Satellite | 24.9 ms              |
| Geostationary Satellite   | 399 ms               |
| Earth to the Moon         | 2157.41 ms           |
| Earth to Mars             | 29.11 minutes        | 
  sources: https://www.rfwireless-world.com/calculators/Network-Latency-Calculator.html and https://wintelguy.com/wanlat.html
