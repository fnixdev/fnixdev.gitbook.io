# @fnixdev@81abdc5

[Permalink](fnixdev-81abdc5.md)

 Showing with **4 additions** and **4 deletions**.

1.  +4 −4 [kannax/plugins/bot/alive.py](fnixdev-81abdc5.md#diff-8d64e0cac48f839c6c6b232613770975a5963cbe96b5eefc56575bde07cc7f2f)

|  | @@ -227,13 +227,13 @@ async def check\_media\_link\(media\_link: str\): |  |
| :--- | :--- | :--- |
|  |  |  @staticmethod |
|  |  |  def alive\_info\(\) -&gt; str: |
|  |  |  alive\_info\_ = f""" |
|  |  | [ **KannaX**](https://t.me/kannaxupdates) **is Up and Running.** |
|  |  |  &lt;b&gt;Yes master &lt;a href="https://t.me/kannaxupdates"&gt;KannaX it's alive. |
|  |  |  |
|  |  |  ◇─◇──◇────★ KannaX ★─────◇──◇─◇ |
|  |  |  ▫️ \`Version\` : \_\_v{get\_version\(\)}\_\_ |
|  |  |  ▫️ \`Versão\` : \_\_v{get\_version\(\)}\_\_ |
|  |  |  ▫️ \`Python\`. : \_\_v{versions.\_\_python\_version\_\_}\_\_ |
|  |  |  ▫️ \`Uptime\`. : \_\_{kannax.uptime}\_\_ |
|  |  |  ▫️ \`Mode\` : \_\_{Bot\_Alive.\_get\_mode\(\)}\_\_ |
|  |  |  ▫️ \`Atividade\`. : \_\_{kannax.uptime}\_\_ |
|  |  |  ▫️ \`Modo\` : \_\_{Bot\_Alive.\_get\_mode\(\)}\_\_ |
|  |  |  ◇─◇──◇────★ ───── ★─────◇──◇─◇ |
|  |  |  """ |
|  |  |  return alive\_info\_ |
|  |  |  |

