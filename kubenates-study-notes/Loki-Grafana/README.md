Loki: like Prometheus, but for logs.

A Loki-based logging stack consists of 3 components:
- promtail is the agent, responsible for gathering logs and sending them to Loki.(promtail是 agent，负责收集日志并将其发送给 Loki。)
- loki is the main server, responsible for storing logs and processing queries.(loki是主服务器，负责存储日志和处理查询。)
- Grafana for querying and displaying the logs.

![](../images/chx/loki-arch.png)

---


1. getting started docs: https://github.com/grafana/loki/blob/master/production/README.md

2. usage docs: https://github.com/grafana/loki/blob/master/docs/usage.md

3. Promtail documentation: https://github.com/grafana/loki/blob/master/docs/promtail-setup.md



