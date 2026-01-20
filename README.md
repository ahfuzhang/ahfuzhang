# Repos that might be useful to you

* Observability
  - Logging
    - VictoriaLogs
      - Grafana Panel: [VictoriaLogsExplorer](https://github.com/ahfuzhang/VictoriaLogsExplorer), A grafana panel for explorer logs on VictoriaLogs.
      - (tools)(rust) [log-generator](https://github.com/ahfuzhang/log-generator), to generate HAProxy format log, use to test Vector / VictoriaLogs.
      - (experimental) [VictoriaLogs_AVX2](https://github.com/ahfuzhang/VictoriaLogs_AVX2), The plan is to try using the avx2 instruction set to optimize performance based on the official VictoriaLogs version.
  - Metrics
    - VictoriaMetrics
      - Book: [InsideVictoriaMetrics](https://github.com/ahfuzhang/InsideVictoriaMetrics), An in-depth eBook on VictoriaMetrics and VictoriaLogs.
      - (notes/comments) [victoria-metrics-1.72.0](https://github.com/ahfuzhang/victoria-metrics-1.72.0), source code from VictoriaMetrics, with chinese comment.
      - (tool) [vmfile](https://github.com/ahfuzhang/VictoriaMetrics_cluster_v1.96.0), a tool for import/export VictoriaMetrics data files.
      - (project/deployment) [deploy_VictoriaMetrics_cluster](https://github.com/ahfuzhang/deploy_VictoriaMetrics_cluster), Provides various scripts for deploying VistoriaMetrics cluster.
* Programming language
  - golang
    - [Doc/Note] [learning_go_plan9_assembly](https://github.com/ahfuzhang/learning_go_plan9_assembly),  Collect various materials in the process of learning go plan9 assembly and share notes.
    - (tools) [file_line](https://github.com/ahfuzhang/file_line), Like `__FILE__/__LINE__` of C: use go generate to get source code line number at compile time.
    - (lib) [cowmap](https://github.com/ahfuzhang/cowmap), Copy-On-Write Map (CowMap), Optimized for small data environments with very large reads and very small writes.
  - C#
    - [WIP]  [QiWa](https://github.com/ahfuzhang/QiWa), A microservice development framework implemented in C#.
* Doc / Notes
  - [code_comments](https://github.com/ahfuzhang/code_comments)，comment code with Chinese.
  - (Articles) [life_of_mine](https://github.com/ahfuzhang/life_of_mine), blogs written by me.
  - (notes/comments) [rust-hashbrown-v0.12.0](https://github.com/ahfuzhang/rust-hashbrown-v0.12.0), A hashtable implement coded by rust lang. With Chinese comment.
