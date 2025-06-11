# Thinkkata Deployment

## Domain: thinkkata.ai

Domain name purchased through Vercel on 6/10/25 for $149

## Template: Next.js AI Chatbot

### AI: Groq (api-key-lightBlue-island)

Account: GitHub

API Key:

```
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
```

Curl:

```CURL
curl https://api.groq.com/openai/v1/chat/completions -s \
-H "Content-Type: application/json" \
-H "Authorization: Bearer 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" \
-d '{
"model": "meta-llama/llama-4-scout-17b-16e-instruct",
"messages": [{
    "role": "user",
    "content": "Explain the importance of fast language models"
}]
}'
```



### Storage: Neon (neon-fuchsia-flower)