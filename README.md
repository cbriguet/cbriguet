# Christophe Briguet

**Cyber security product leader.** I work on security products by day, and build small,
sharp tools for the questions security teams keep answering in spreadsheets.

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

---

### What I'm thinking about

- **Graph analytics on security data** — relationships are usually the signal; rows rarely are.
- **Where ML actually beats a good heuristic.** A narrower set of problems than the market implies, and worth being honest about which side a given problem falls on.
- **Capacity and cost as product problems**, not procurement afterthoughts.

### What I'm up for

Conversations about a **security startup** — founding, advising, or comparing notes.
Also happy to argue about SIEM sizing with anyone who still does it in a spreadsheet.

[briguet.me](https://briguet.me) · [@cbriguet](https://x.com/cbriguet)
