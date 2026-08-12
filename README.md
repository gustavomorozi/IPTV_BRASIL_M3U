# IPTV_BRASIL_M3U

Uma rede colaborativa e descentralizada de IPTV/M3U. O sistema permite que a comunidade mantenha a lista sempre atualizada, substituindo links inativos por novas rotas funcionais.

**Diretrizes Principais:**
* **Prioridade de Qualidade:** Busque sempre enviar links nas resoluções FHD, HD e, por último, SD.
* **Substituição e Melhoria:** Quando um canal cair ou se você encontrar uma rota de melhor qualidade, você pode submeter o novo link para atualizar o antigo.

---

## ⚖️ Aviso Legal (Disclaimer)

Este projeto **não hospeda, não armazena, não transmite e não retransmite** nenhum arquivo de vídeo, streaming ou sinal de TV. 

Todos os links (URLs) presentes nesta lista são de responsabilidade exclusiva de **fontes terceiras** e são coletados de forma colaborativa por usuários a partir de conteúdos já disponíveis publicamente na internet. 

A comunidade atua unicamente como um agregador e indexador de informações (semelhante a um mecanismo de busca). Portanto, os mantenedores, criadores e colaboradores deste repositório **não possuem qualquer responsabilidade legal, técnica ou autoral** sobre o conteúdo transmitido pelas rotas de terceiros. Se algum link violar direitos de imagem ou copyright, a responsabilidade recai inteiramente sobre o servidor original que hospeda e transmite o arquivo.

---

## 🔗 Link Oficial da Lista

Para carregar a lista em seu player, utilize a URL direta abaixo (Raw):
`https://raw.githubusercontent.com/gustavomorozi/IPTV_BRASIL_M3U/refs/heads/main/Canais.m3u`

---

## 📝 Regras de Contribuição

Para manter a integridade da nossa rede e evitar a quebra do arquivo final, toda submissão **deve seguir rigorosamente as regras abaixo**. *Pull Requests* ou submissões fora do padrão serão rejeitados automaticamente pelo sistema.

### 🛠️ Como Editar a Lista (Ferramenta Recomendada)
Para facilitar a edição e a adição de canais sem quebrar a formatação do arquivo, recomendamos utilizar o site:
**👉 [Awesome M3U Editor](https://arazgray.github.io/awesome-m3u-editor/)**

### 1. Organização e Acervo (Regras de Ouro)
* **Canal Único:** Cada canal deve ter **apenas um único bloco `#EXTINF`**. Não crie duplicações ou múltiplas opções para o mesmo canal no arquivo.
* **Melhoria de Qualidade:** Caso você queira melhorar a estabilidade ou qualidade (FHD/HD) de um canal já existente, você pode subir o novo link substituindo o anterior.
* **Canais em branco / Sem link (ND):** 
  * Se você for **adicionar um canal que ainda não possui link**, coloque a sigla **(ND)** ao lado do nome (ex: `A&E (ND)`) e utilize obrigatoriamente a URL fixa `http://url-falsa.com/stream.m3u8`. Isso garante que ele apareça na estrutura do M3U.
  * Quando você editar um canal (ND) existente e fornecer um link válido, **lembre-se de remover a sigla (ND)** do título e substituir a URL falsa pelo link real.
* **NÃO adicione canais novos:** A lista mantém um acervo fixo. Se você quiser sugerir um canal inédito, **nos avise antes de submeter** (através de uma *Issue* ou canal de comunicação do projeto).

### 2. Padrão de Formatação M3U
Utilize sempre a estrutura padrão contendo as tags obrigatórias: `tvg-id`, `tvg-name`, `tvg-logo` e `group-title`.

> 📌 **Atenção:** Insira as URLs de forma limpa. Não utilize formatação de hiperlink do Markdown (como `[link](url)`) dentro do arquivo final, pois isso quebra a leitura do player.

**Exemplo exato de formatação aceita:**

```m3u
#EXTINF:-1 tvg-id="BAND HD" tvg-name="BAND HD" tvg-logo="https://i.imgur.com/nCJNjyN.png" group-title="Canais",BAND
https://megaflix.mgfiles.lat/baf6746727bd762be4571e2e4fb62cde/file.m3u8
```
