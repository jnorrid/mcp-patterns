# mcp-patterns
A series of implementations, progressing from from trivial/single-machine, to more complex/distributed, for showcasing Model Context Protocol (MCP) patterns.

## Inventory
**Type 1 [ISCSS-Claude]:** Interactive, Single-Client, Single-Server, Anthropic Claude Sonnet 3.7 LLM

**Type 2 [ISCSS-Ollama]:** Interactive Single-Client, Single-Server, Ollama Mistral-7B LLM

**Type 3 [IMCMS-Claude]:** Interactive Multi Client, Multi-Server, Anthropic Claude Sonnet 3.7 LLM

**Type 4 [IMCMS-Ollama]:** Interactive Multi-Client, Multi-Server, Anthropic Ollama Mistral-7B LLM

**Type 5 [MSCSS-Claude]:** Microservice, Single-Client, Single-Server, Anthropic Claude Sonnet 3.7 LLM 

**Type 6 [MSCSS-Ollama]:** Microservice, Multi-Client, Multi-Server, Ollama Mistral-7B LLM

## Future Research and Derivatives:
**Streams:** One or more servers provide additional context to the LLM by interacting with streaming infrastructure (Kafka, Pulsar, MQTT, RabbitMQ, OpenMQ)

**Exhaust:** Aggregated LLM response post execution is stored in database and vectorized.

**Closed-Loop Streams:** Aggregated LLM response post execution is published to streaming infrastructure (Kafka, Pulsar, MQTT, RabbitMQ, OpenMQ)

