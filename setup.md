# Pre requisites

## PG Vector

1. <https://github.com/pgvector/pgvector?tab=readme-ov-file#docker>
2. docker run --name pg-vector -p 5433:5432 -e POSTGRES_PASSWORD=mysecretpassword -d {image-name or image-id}

## Ollama

- <https://ollama.com/>

## LLM

- <https://ollama.com/library/llama3.1>

## Embeddings model

- <https://ollama.com/library/nomic-embed-text>
- FYI : This model has embedding dimensions of 768. The same should should be set in the db schema.

## AI SDK Ollama provider

- <https://sdk.vercel.ai/providers/community-providers/ollama>
