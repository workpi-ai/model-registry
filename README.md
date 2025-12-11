# Model Registry

A centralized metadata repository for AI models.

## What is this?

Model Registry provides standardized YAML-based metadata for AI models from various providers, including:

- **Model capabilities**: context limits, features (tool_use, reasoning, structured_output)
- **API configurations**: api_format, endpoint, parameters  
- **Provider information**: authentication, base_url, description

**Supported providers**: Anthropic, OpenAI, Google Gemini, DeepSeek, Moonshot, Qwen, xAI, AWS Bedrock, OpenRouter, and more.

## Usage

### Go SDK

```bash
go get github.com/workpi-ai/model-registry-go
```

See: [model-registry-go](https://github.com/workpi-ai/model-registry-go)
