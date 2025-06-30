Segmented delivery is a technique where a large video (or audio) file is split into many small pieces, called **segments** (usually 2–10 seconds each). These segments are delivered to the client (browser/app) over regular HTTP as needed.

### **Why use segmented delivery?**

- **Adaptive Bitrate Streaming:** The player can request low- or high-quality segments depending on the user’s network speed.
- **Fast Startup:** The player only needs the first segment to begin playback, so videos start quickly.
- **Efficient Buffering:** Only a few segments are loaded ahead, so less bandwidth is wasted if the user skips or stops.
- **Seamless Seeking:** Jumping to a new part of the video just means requesting different segments, not downloading the whole file.
- **Scalability:** Segments are static files, easily cached and distributed by CDNs.