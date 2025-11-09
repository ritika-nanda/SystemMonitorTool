
# Project Report: System Monitor Tool

## 1. Title
**System Monitor Tool (Console-based, Linux)**  
An interactive terminal-based system monitor similar to `top` that shows overall CPU/memory usage and lists running processes with per-process CPU% and memory% and supports killing processes.

---

## 2. Codes
Below is the main source file used for the project.

```cpp
// See attached file: system_monitor.cpp
// (Full code saved in system_monitor.cpp in repository)
```

> For convenience the full code file `system_monitor.cpp` is included alongside this report.

---

## 3. Full screenshots
Include the following screenshots in this section (replace placeholders with actual images):
1. Compilation screenshot: `g++ system_monitor.cpp -o monitor -std=c++17 -O2`
   - [screenshot: compile.png]
2. Running screenshot showing system stats and process list
   - [screenshot: running.png]
3. Example of killing a process: issued `k <pid>` and confirmation
   - [screenshot: kill1.png, kill2.png, kill3.png]
4. Example of quiting the program : issued 'q' command and enter
   - [screenshot: quiting.png, quited.png]

---

## Build & Run Instructions

1. Clone repository (after you push code to GitHub):
   ```
   git clone <your-repo-url>
   cd System-Monitor-Tool
   ```

2. Compile:
   ```
   g++ system_monitor.cpp -o monitor -std=c++17 -O2
   ```

3. Run:
   ```
   sudo ./monitor
   ```

   (Some process info or kill operations may require elevated privileges depending on system policies.)

---

## GitHub Repository Structure (suggested)

```
System-Monitor-Tool/
├─ system_monitor.cpp
├─ Readme.md
├─ system_monitor_tools.pdf
├─ screenshots/
│  ├─ compile.png
│  ├─ running.png
│  ├─ quiting.png
│  ├─ quited.png
│  ├─ kill1.png
│  ├─ kill2.png
│  └─ kill3.png
```

---

## Notes & Extension Ideas (highlight if extended)
If you extended the project (e.g., added network monitoring, CSV logs, web UI), rename title to **Advanced System Monitor Tool** and highlight the new title in **yellow** in the final submitted PDF.
