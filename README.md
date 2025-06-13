
# Teamly.py for Python

Teamly API ile kolayca entegre olmanızı sağlayan, modüler ve genişletilebilir Python SDK'sı. Tüm HTTP endpoint'lerini ve WebSocket olaylarını kapsar.

## Özellikler
- Tüm API kaynakları için ayrı modüller
- REST endpoint desteği (GET, POST, PUT, DELETE)
- WebSocket ile canlı veri akışı
- Dosya yükleme ve özel izin sabitleri
- Kolay genişletilebilir mimari

## Kurulum
```bash
pip install -r requirements.txt
```

## Başlangıç
```python
from teamly_sdk import TeamlyClient

client = TeamlyClient(token="your_api_token")

channels = client.channels.get_team_channels(team_id="12345")
print(channels.json())
```

## Katkı 
Bu SDK, geliştiriciler için açık kaynaklıdır. 

## Lisans
MIT License

