## CoinDCX Market Data Automation Suite

A professional-grade automation and analytics suite for **crypto market data, order placement, and Excel integration**.  
Developed with **Python, WebSockets, and REST APIs**, this tool enables **real-time market tracking, order execution, and reporting**.

---

##  Features
- **Live Market Data**: Real-time bid/ask updates from CoinDCX WebSocket.
- **Automated Order Placement**: Place, track, and manage trades seamlessly.
- **Excel Integration**: Export live data & stats directly into Excel dashboards.
- **Profiling & Optimization**: Includes performance benchmarks and profiling reports.
- **Executable Build**: No Python setup required — use the `.exe` directly.

---


##  **Demo Video**
[Click here to watch the demo](https://drive.google.com/file/d/1Jhqa0N_nY1vBKIGLQwKr6QsjefS3IQYr/view?usp=sharing)

##  Performance Profiling

This project was performance-tested using Python’s built-in `cProfile` and `pstats`.  
The analysis helped in identifying bottlenecks and optimizing Excel interaction and socket communication.

### Highlights:
- Optimized `process_batch_updates` and `process_queues` functions.
- Reduced overall runtime from **227s → 96s → 55s** in[profile.stats%.txt](https://github.com/user-attachments/files/22181222/profile.stats.txt)
 different optimization phases.
- Major improvements in Excel COM interactions (`xlwings`).

 See full reports in:
 - [`profile.stats%.txt`]()
 

