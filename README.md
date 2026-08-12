# IPTV_BRASIL_M3U
Uma rede colaborativa e descentralizada de IPTV/M3U. O sistema permite que qualquer usuário submeta novos links quando um canal cai, 
-> Sempre priorizar: FHD, HD e SD.
-> Quando um canal cai, qualquer usuário pode submeter uma nova rota.


## 📝 Regras de Contribuição e Inserção de Links

Para manter a integridade da nossa rede e evitar a quebra do arquivo final, toda submissão **deve seguir rigorosamente as regras abaixo**. Pull Requests ou submissões fora do padrão serão rejeitados automaticamente pelo pipeline.

### 1. Preservação do Acervo (Regra de Ouro)
* **SEMPRE mantenha os canais que já estão na lista.** 
* O envio de novos links serve para criar **redundância** e **melhorar a qualidade** da rede, e não para substituir a base que já existe.
* 
* **Criação de Novos Canais:** Se você for adicionar um canal inédito (que ainda não existe no repositório), **você deve avisar a comunidade**.

### 2. Padrão de Formatação M3U
Utilize sempre a estrutura padrão com as tags `tvg-id`, `tvg-name`, `tvg-logo` e `group-title`.

📌 **Exemplo exato de formatação aceita:**
```text
#EXTINF:-1 tvg-id="BAND HD" tvg-name="BAND HD" tvg-logo="[https://i.imgur.com/nCJNjyN.png](https://i.imgur.com/nCJNjyN.png)" group-title="Canais",BAND
[https://megaflix.mgfiles.lat/baf6746727bd762be4571e2e4fb62cde/file.m3u8](https://megaflix.mgfiles.lat/baf6746727bd762be4571e2e4fb62cde/file.m3u8)

### 3. Ao carregar usar o caminhao:
https://raw.githubusercontent.com/gustavomorozi/IPTV_BRASIL_M3U/refs/heads/main/Canais.m3u
