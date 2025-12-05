# Backend Kubernetes Configuration

## Secret 설정 방법

1. `secret.yaml` 파일의 플레이스홀더를 실제 API 키로 교체:
   - `<YOUR_OPENAI_API_KEY>`: OpenAI API 키
   - `<YOUR_LANGCHAIN_API_KEY>`: LangChain API 키  
   - `<YOUR_TAVILY_API_KEY>`: Tavily API 키
   - `<YOUR_STABILITY_API_KEY>`: Stability AI API 키
   - `<YOUR_GEMINI_API_KEY>`: Google Gemini API 키

2. Kubernetes에 적용:
   ```bash
   kubectl apply -f secret.yaml
   ```

**주의사항**: 실제 API 키가 포함된 파일은 절대 Git에 커밋하지 마세요!