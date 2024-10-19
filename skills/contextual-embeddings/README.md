# Enhancing RAG with contextual Retrieval

## Preamble

This example is adapted from anthropic's [contextual embeddings cookbook](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/contextual-embeddings) to work with [Amazon OpenSearch serverless](https://docs.aws.amazon.com/opensearch-service/latest/developerguide/serverless-overview.html) and [Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html)/[SageMaker Jumpstart](https://docs.aws.amazon.com/sagemaker/latest/dg/jumpstart-foundation-models.html) endpoints.

## Changes

1. Local Vector DB -> OpenSearch serverless
2. Claude 3 on Anthropic endpoints -> Claude 3 on Bedrock
3. VoyageAI embedding endpoint -> Bge-m3 on Sagemaker (Jumpstart)
4. Reranker on Cohere endpoints -> Cohere reranker 3 on Sagemaker (Jumpstart)