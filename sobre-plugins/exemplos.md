# Exemplos

## Exemplo para comandos. <a id="example-command"></a>

```python
from kannax import kannax, Message

@kannax.on_cmd("test", about="texto de ajuda para este comando")
async def test_cmd(message: Message):
   # algumas outras coisas
   await message.edit("testando...")
   # algumas outras coisas
```

## Exemplos para Filters <a id="example-filter"></a>

```python
from kannax import kannax, Message, filters

@kannax.on_filters(filters.me & filters.private)
async def test_filter(message: Message):
   # algumas outras coisas
   await message.reply(f"you typed - {message.text}")
   # algumas outras coisas
```

