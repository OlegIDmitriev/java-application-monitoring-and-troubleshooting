## Modern applications architecture and deployment: What tiers do we monitor? (1h)
| Tier 
|------
| Application logic layers: UI/P, API/C, BL/S, DAL/R | 
| Application caching 
| Thread Pool | Thread count
| JPA Caching | Cach
| JPA subsystem 
| Connection Pools | Connections pool, lifetime
| JDBC subsystem 
| Framework configuration with profiles
| Framework for Spring modules management |  Beans lifecycle, Beans count
| Framework for Web/SOAP/REST application expose
| Framework for Application | Log monitoring
| Application Server/Servlet Container | TCP/UDP Connections, HTTP response time, Response Code, Negative Response count
| JVM: application debug API | ???
| JVM: application profiling API | IO Resources, Objects, 
| JVM: universal monitoring API | Classes
| JVM: threads, IO | Count, IO Wait
| JVM: memory, GC | Heap -> Objects details, Generations, GC time, Deleted objects count, GC Schedule
| JVM: process | Utilization
| Container: Networking | Utilization
| Container: Core | Status, Utilization
| Message queues | ??
| DBMS | ??
| OS: Threads | Count
| OS: Processes | RAM Utilization, CPU Utilization, Count, Top
| Hardware: HDD/SSD | IOPS, Available Space
| Hardware: RAM | Available, Swap
| Hardware: CPU | Utilization, Load average
| Hardware: LAN | Utilization
