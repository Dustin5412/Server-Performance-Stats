# Server Performance Stats Tool

A portable, dependency-free Bash script designed to analyze and display critical server performance statistics on any Linux distribution. This tool provides system administrators with an immediate snapshot of resource utilization, helping to identify performance bottlenecks and resource-heavy processes.

### Features
* **CPU & Memory:** Calculates total CPU usage and provides a breakdown of free vs. used memory (including percentages).
* **Storage:** Analyzes disk utilization across the filesystem.
* **Process Tracking:** Identifies the top 5 resource-consuming processes ranked by CPU and memory consumption.
* **System Metadata (Optional):** Displays uptime, OS version, load averages, and security insights like failed login attempts.

## Getting Started
1. **Clone the repository**
    ```
    git clone https://github.com/Dustin5412/Server-Performance-Stats.git
    
    ```
    
2. **Make the script executable**
    ```
    chmod +x server-stats.sh
    ```
3. **Execute the script**  
    ```
    ./server-stats.sh
    ```
