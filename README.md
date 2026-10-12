# Christophe Briguet

**Cyber security product leader.** I work on security products by day, and build small,
sharp tools for the questions people keep answering in spreadsheets: how big a log
deployment has to be, and lately, how a yoga class lands on its music.

---

### 📏 [Logcaliper](https://logcaliper.app) — *size your log deployment before you buy it*

Every SIEM quote turns on two numbers, bytes per event and events per second, and most
of the time both are guessed. Logcaliper measures them, then sizes the deployment.

- **[The profiler](https://logcaliper.app/profiler/)** reads a sample of your own log in
  the browser, with nothing uploaded: lines and bytes reconciled to the byte, the average
  bytes per event, the message templates (a port of Drain, checked cluster by cluster
  against Drain3), the events per second over the time the timestamps cover, and what a
  year of it takes to keep. [Source](https://github.com/cbriguet/logcaliper.app/tree/main/profiler).
- **[The iOS app](https://apps.apple.com/app/id381096276)**, free on iPhone and iPad since
  2010, sizes a whole list of sources: storage at retention, compression, the cluster and
  the number of data nodes. Cited in IBM's Think 2018 QRadar sizing session and on
  Splunk's blog.
- **[Measured event sizes](https://logcaliper.app/sources/)** for 39 products and typical
  event rates for 16 source categories, a page each, and the whole table as a CSV under
  CC BY.

### 🔬 [logstats](https://github.com/cbriguet/logstats) — *finding the shape of unstructured logs*

Automated classification of log records using edit distance and TLSH fuzzy hashing.
Millions of lines collapse into the handful of patterns they really are, which is the
step everything else in log analytics depends on. The profiler above does the same job
in a browser, with Drain.

### 〰️ [Arcbeat](https://arcbeat.yoga) — *music that's intentional, not just there*

A planning tool for yoga teachers. Choose the pose you want the room to land and a track,
see where the music breaks and where it comes back, and build the way up so the landing
pose arrives exactly there, before anyone is on a mat. For Yoga Sculpt it maps a whole
playlist: one line per song with when the beat comes in, where it breaks and the room to
cue. [Open the demo](https://demo.arcbeat.yoga). In validation with teachers now.

---

### What I'm thinking about

- **Graph analytics on security data** — relationships are usually the signal; rows rarely are.
- **Where ML actually beats a good heuristic.** A narrower set of problems than the market implies, and worth being honest about which side a given problem falls on.
- **Capacity and cost as product problems**, not procurement afterthoughts.

### What I'm up for

Conversations about a **security startup** — founding, advising, or comparing notes.
Also happy to argue about SIEM sizing with anyone who still does it in a spreadsheet.

[briguet.me](https://briguet.me) · [@cbriguet](https://x.com/cbriguet)
