# h2console-wildfly

This is a simple H2 Database WAR, used to expose H2's web console.

Access from other hosts is allowed (useful for e.g. Docker containers), and H2's TCP server is started at deploy time. This allows to access databases via e.g. JDBC.

Default H2 TCP port is 9092, which can be changed in web.xml.
