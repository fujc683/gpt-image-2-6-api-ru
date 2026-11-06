<a href="https://gola.apimart.ai/k-0MbOar"><img src="https://raw.githubusercontent.com/fujc683/awesome-gpt-image-2-6-prompts/main/banner.jpg" width="100%" /></a>

# Коллекция промптов GPT Image 2.6

> 252 отобранных промпта с превью, сгруппированы по сценариям. Варианты Flare и Sunburst.

**[👉 Использовать GPT Image 2.6 на APIMart](https://gola.apimart.ai/k-0MbOar)**

`https://gola.apimart.ai/k-0MbOar`

[💰 Цены](https://gola.apimart.ai/k-MGNK9K) · [🔑 Получить API-ключ](https://gola.apimart.ai/k-iXbxtr)

---

## Endpoint

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H "Authorization: Bearer $APIMART_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model":"gpt-image-2.6-flare","prompt":"a red apple","n":1,"size":"1024x1024"}'
```

## Models

| ID | Variant |
|---|---|
| `gpt-image-2.6-flare` | Flare |
| `gpt-image-2.6-sunburst` | Sunburst |

## Parameters

| Field | Type | Description |
|---|---|---|
| `model` | string | model id |
| `prompt` | string | text prompt |
| `n` | int | 1-4 |
| `size` | string | `1024x1024` / `1536x1024` / `1024x1536` |

## Poll

```bash
curl https://api.apimart.ai/v1/tasks/<task_id> -H "Authorization: Bearer $APIMART_API_KEY"
```

---

## License

CC BY 4.0
