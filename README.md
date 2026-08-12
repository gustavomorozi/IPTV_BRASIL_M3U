# IPTV_BRASIL_M3U

Uma rede colaborativa e descentralizada de IPTV/M3U. O sistema permite que a comunidade mantenha a lista sempre atualizada, substituindo links inativos por novas rotas funcionais.

**Diretrizes Principais:**
* **Prioridade de Qualidade:** Busque sempre enviar links nas resoluções FHD, HD e, por último, SD.
* **Substituição e Melhoria:** Quando um canal cair ou se você encontrar uma rota de melhor qualidade, você pode submeter o novo link para atualizar o antigo.

---

## 🔗 Link Oficial da Lista

Para carregar a lista em seu player, utilize a URL direta abaixo (Raw):
`https://raw.githubusercontent.com/gustavomorozi/IPTV_BRASIL_M3U/refs/heads/main/Canais.m3u`

---

## 📝 Regras de Contribuição

Para manter a integridade da nossa rede e evitar a quebra do arquivo final, toda submissão **deve seguir rigorosamente as regras abaixo**. *Pull Requests* ou submissões fora do padrão serão rejeitados automaticamente pelo sistema.

### 1. Organização e Acervo (Regras de Ouro)
* **Canal Único:** Cada canal deve ter **apenas um único bloco `#EXTINF`**. Não crie duplicações ou múltiplas opções para o mesmo canal no arquivo.
* **Melhoria de Qualidade:** Caso você queira melhorar a estabilidade ou qualidade (FHD/HD) de um canal já existente, você pode subir o novo link substituindo o anterior.
* **NÃO adicione canais novos:** A lista mantém um acervo fixo. Se você quiser sugerir um canal inédito, **nos avise antes de submeter** (através de uma *Issue* ou canal de comunicação do projeto).

### 2. Padrão de Formatação M3U
Utilize sempre a estrutura padrão contendo as tags obrigatórias: `tvg-id`, `tvg-name`, `tvg-logo` e `group-title`.

> 📌 **Atenção:** Insira as URLs de forma limpa. Não utilize formatação de hiperlink (como `[link](url)`) dentro do arquivo final, pois isso quebra a leitura do player.

**Exemplo exato de formatação aceita:**

```m3u
#EXTINF:-1 tvg-id="BAND HD" tvg-name="BAND HD" tvg-logo="[https://i.imgur.com/nCJNjyN.png](https://i.imgur.com/nCJNjyN.png)" group-title="Canais",BAND
[https://megaflix.mgfiles.lat/baf6746727bd762be4571e2e4fb62cde/file.m3u8](https://megaflix.mgfiles.lat/baf6746727bd762be4571e2e4fb62cde/file.m3u8)
