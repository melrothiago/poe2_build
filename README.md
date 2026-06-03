# PoE2 Builds

## O que e

Uma pagina HTML que faz uma **pesquisa inteligente** em **8 fontes da comunidade**
(Maxroll, Mobalytics, Icy Veins, PoE Ninja, Reddit, Forum GGG, PoeBuilds.io, Poe-Vault)
para encontrar as melhores builds de **Path of Exile 2** (Runes of Aldur / Return of the Ancients 0.5.0)
e gerar um relatorio comparativo completo com **DeepSeek V4 Flash**.

**Nao precisa instalar nada. Nao precisa de servidor.**
**So abrir o arquivo no navegador e usar.**

---

## Requisitos

- Navegador moderno (Chrome, Edge, Firefox, Safari)
- Conexao com a internet
- (Opcional) Chave de API **DeepSeek** para analise completa por IA

## Como usar

1. Abra o arquivo `poe2builds.html` no navegador

2. Clique na classe que voce quer pesquisar

3. Clique em **Pesquisar**

4. Aguarde enquanto o app coleta dados de todas as 8 fontes

5. Leia o **relatorio completo** na pagina

### Com chave DeepSeek (recomendado)

1. Clique na engrenagem (⚙) no canto superior direito
2. Cole sua chave de API do DeepSeek (comeca com `sk-...`)
3. Clique em Salvar
4. Agora toda pesquisa gera analise completa com:

   - Meta overview da classe
   - Melhores builds com links diretos
   - Habilidades e Support Gems
   - Uniques recomendados
   - Comparacao entre builds
   - Dicas de leveling e endgame
   - Mecanicas importantes

### Sem chave DeepSeek

O app funciona normalmente e coleta dados de todas as fontes, mas mostra apenas
os titulos das builds encontradas.

## Fontes consultadas

| Fonte | URL | Tipo de acesso |
|---|---|---|
| **Maxroll** | https://maxroll.gg/poe2/build-guides | Sitemap XML via proxy |
| **Mobalytics** | https://mobalytics.gg/poe-2/builds | Site via proxy |
| **Icy Veins** | https://www.icy-veins.com/poe2/builds/ | Site via proxy |
| **PoE Ninja** | https://poe.ninja/poe2/builds | Site via proxy |
| **Reddit** | https://www.reddit.com/r/PathOfExile2Builds/ | API oficial |
| **Forum GGG** | https://www.pathofexile.com/forum/ | Site via proxy |
| **PoeBuilds.io** | https://poebuilds.io/poe2 | Site via proxy |
| **Poe-Vault** | https://www.poe-vault.com/poe2/builds | Site via proxy |

## Classes

### Disponiveis (8)
- Monk (🥋) — 25% dos jogadores
- Huntress (🏹) — 17%
- Ranger (🏹) — 14%
- Mercenary (🔫) — 4%
- Sorceress (🪄) — 5%
- Witch (💀) — 4%
- Warrior (🛡️) — 2%
- Druid (🐻) — 4%

### Bloqueadas (4 — em breve)
- Marauder 🔒
- Shadow 🔒
- Duelist 🔒
- Templar 🔒

## Como funciona

1. O app coleta dados brutos de todas as 8 fontes simultaneamente
2. Se voce configurou uma chave DeepSeek, envia os dados para analise por IA
3. O DeepSeek retorna um JSON estruturado com meta, builds, skills, uniques, dicas
4. O app renderiza o relatorio em secoes no estilo Maxroll

## Solucao de problemas

**Relatorio mostra poucos resultados / fontes com 0 builds**
A pagina depende de proxies publicos para acessar alguns sites.
Se um proxy estiver fora do ar, os dados desse site serao pulados.
O app sempre mostra o que conseguiu coletar.

**"Nenhuma build encontrada"**
Verifique sua conexao com a internet. Se estiver online, tente
novamente em alguns minutos — os proxies podem estar ocupados.

**Analise DeepSeek nao aparece**
Verifique se sua chave DeepSeek comeca com `sk-` e esta correta.
O DeepSeek tem rate limits: 2500 requisicoes simultaneas (Flash).

**Quer atualizar os dados?**
Use **Ctrl+F5** no navegador para recarregar sem cache.

## Termos

Este app e uma ferramenta de consulta que acessa sites publicos
para coletar informacoes sobre builds de Path of Exile 2.

**POE2 Builds v1.0 — Runes of Aldur / Return of the Ancients 0.5.0**
