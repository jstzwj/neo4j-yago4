FROM neo4j:5.1.0
WORKDIR /neo4j_server

ENV NEO4J_server_memory_pagecache_size=16G
ENV NEO4J_server_memory_heap_initial__size=8G
ENV NEO4J_server_memory_heap_max__size=16G
ENV NEO4J_db_memory_pagecache_warmup_enable=true

ENV NEO4J_server_unmanaged__extension__classes=n10s.endpoint=/rdf
ENV NEO4J_PLUGINS='["apoc", "n10s"]'
ENV NEO4J_AUTH=neo4j/QAZqaz1234
