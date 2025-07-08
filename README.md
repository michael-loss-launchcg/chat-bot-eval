# Wa-Bot - AI Chatbot with AWS Integration

## Overview
Wa-Bot is a sophisticated chatbot implementation demonstrating advanced integration with AWS services, particularly Amazon Bedrock. The project showcases practical experience with AI/ML services, cloud computing, and modern Python development.

## Key Features
- Integration with Amazon Bedrock for AI model inference
- Support for multiple foundation models (including Claude and Nova)
- Multi-language detection and response capability
- Context-aware conversations with knowledge base integration
- Chat history management and persistence
- Hybrid search functionality for improved response accuracy

## Technical Stack
- **Cloud Services**: AWS Bedrock
- **AI/ML**: Foundation Models (Claude, Nova)
- **Programming**: Python
- **Search**: OpenSearch integration
- **Authentication**: AWS IAM and authentication handling

## Core Components
- `ChatHandler`: Manages conversation state and history
- `get_embedding`: Generates text embeddings using Amazon Titan
- `get_context`: Implements knowledge base retrieval with vector search
- `get_response`: Handles AI model inference and response generation
- `answer_query`: Orchestrates the complete query-response pipeline

## Implementation Highlights
- Secure AWS credential management
- Access to OpenAI as well as AWS Bedrock Models
- Language detection for multilingual support
- Hybrid search combining vector and semantic search
- Configurable model parameters for response generation
- Robust error handling and response processing
- Evaluation capabilities (See below)

## Evaluation capabilities
- Any llm can evaluate the prior response based on prompt-driven criteria
- The is a batch mode that allows multiple LLMs to respond to list of prompts and record the responses an meta-data
- A Batch judge Mode allows an targted LLM to evaluate the batch reposnses.
- A swarm-mode tht uses a thread-farm to process batch queries and evaluations as high as 50 at a time
- A final mode that outputs a .cvs with the aggregated evaluation metric for visualizations and analysis in excel or another BI app.

## Professional Applications
This project demonstrates expertise in:
- Large Language Model (LLM) integration
- Enterprise-grade cloud service implementation
- Secure API handling and authentication
- Scalable conversation management
- Production-ready code organization

## Future Enhancements
- Enhanced conversation context management
- Additional foundation model support
- Advanced prompt engineering capabilities
- Extended multilingual capabilities
- Performance optimization for large-scale deployment

## Skills Demonstrated
- AWS Cloud Services
- AI/ML Integration
- Python Development
- API Design
- System Architecture
- Security Best Practices
- OpenAI


