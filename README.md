Este projeto contém mapas heatmap profissionais mostrando a distribuição espacial de óbitos por leptospirose na cidade de São Paulo, Brasil, durante o período de 2007-2025.

Os mapas utilizam dados do SINAN (Sistema de Informação de Agravos de Notificação) integrados com caracterização molecular de isolados de Leptospira spp. do estudo de Di Azevedo & Lilenbaum (2025) publicado em Acta Tropica.


📊 Dados Principais

Resumo Epidemiológico


Total de Óbitos: 704
Total de Casos Confirmados: 4.055
Taxa de Letalidade (CFR): 17,4%
Período: 2007-2025 (19 anos)
Bairros Mapeados: 43
Regiões Administrativas: 6


Distribuição por Região Administrativa

RegiãoÓbitos% do TotalPrincipais BairrosLeste16924,0%Itaquera, São Miguel, Ermelino MaranhãoCentro14720,9%Sé, Brás, Pari, TatuapéNorte12417,6%Tremembé, Jaçanã, MandaquiOeste12117,2%Lapa, Butantã, PinheirosSul9313,2%Jabaquara, Grajaú, SocorroSudeste497,0%Ipiranga, Saúde, Vila Mariana

Caracterização Molecular (n=67)

Espécies:


Leptospira interrogans: 57 (85,1%)
Leptospira santarosai: 10 (14,9%)


Sorogrupos Principais (n=31):


Icterohaemorrhagiae: 6 (8,96%) - Crítico
Pomona: 7 (10,4%)
Bananal/Sejroe: 5 (7,46%)


Hospedeiros (n=67):


Cães (Canis familiaris): 47 (70,1%) - Principal
Porcos (Sus scrofa): 17 (25,4%)
Outros: 3 (4,5%)


Ambiente:


Urbano: 50 (74,6%)
Rural: 17 (25,4%)



🗺️ Mapas Incluídos

1. Mapa Interativo com Heatmap Folium

Arquivo: mapa_heatmap_sp_completo.html

Descrição

Mapa interativo baseado em Folium com visualização de heatmap dinâmica. Mostra a intensidade de óbitos através de um gradiente de cores (amarelo → marrom/vermelho) sobreposto a um mapa da cidade de São Paulo com marcadores para cada bairro.

Características


✅ Interativo: zoom, pan (arrastar), clique nos marcadores
✅ Heatmap em gradiente: cores representam intensidade de óbitos
✅ Marcadores coloridos: circulares, tamanho proporcional aos óbitos
✅ Popups informativos: clique para ver detalhes do bairro
✅ Legenda integrada: explicação de cores e símbolos
✅ Responsivo: funciona em desktop e mobile


Cores do Heatmap

#fff7bc (Amarelo claro) ─→ baixa intensidade
#fee391 (Amarelo)
#fec44f (Amarelo-laranja)
#fe9929 (Laranja)
#d95f0e (Marrom escuro) ─→ alta intensidade

Como Usar


Abra o arquivo em qualquer navegador web
Use zoom (scroll/pinch) para aproximar
Arraste para explorar diferentes áreas
Clique nos círculos para informações do bairro
Observe o heatmap de fundo para padrões de concentração


Dados Exibidos por Bairro


Nome do bairro
Número de óbitos
Região administrativa
Coordenadas geográficas (latitude/longitude)



2. Heatmap Interpolado com Contorno

Arquivo: heatmap_interpolado_sp.png

Descrição

Mapa estático de alta resolução utilizando interpolação cúbica para suavizar dados discretos (por bairro) e gerar um campo contínuo. Inclui linhas de contorno (isopletas) que mostram curvas de igual intensidade.

Características


✅ Interpolação suavizada: transições graduais entre áreas
✅ Contourf (preenchimento): 20 níveis de cor
✅ Linhas de contorno: 10 isolinhas com rótulos numéricos
✅ Scatter overlay: pontos reais em vermelho escuro
✅ Colorbar: escala numérica de óbitos
✅ Alta resolução: 300 dpi, pronto para impressão


Interpretação


Área vermelha/laranja: alta concentração de óbitos
Área amarela: concentração moderada
Linhas pretas: curvas de isointensidade (valores iguais)
Números nas linhas: quantidade estimada de óbitos


Uso Recomendado


📄 Incluir em trabalhos acadêmicos
🎓 Apresentações e seminários
📊 Relatórios técnicos
🖨️ Impressão de alta qualidade



3. Hexbin Heatmap

Arquivo: hexbin_heatmap_sp.png

Descrição

Agregação de dados por células hexagonais. Cada hexágono representa uma área geográfica e sua cor/intensidade reflete o total de óbitos naquela região.

Características


✅ Agregação por grid hexagonal: 12 células por lado
✅ Contagem agregada: soma de óbitos por célula
✅ Colormap YlOrRd: amarelo (baixo) → vermelho (alto)
✅ Marcador de estrela: mostra localização dos bairros
✅ Colorbar: escala agregada


Vantagens


Reduz sobreposição visual
Facilita identificação de "clusters"
Mostra padrões de concentração geográfica
Menos poluído visualmente que scatter simples


Hotspots Identificados


Leste (principalmente): maior concentração de células vermelhas
Centro: segundo maior concentração
Sudeste: menor concentração



4. Mapa por Regiões Administrativas

Arquivo: mapa_regioes_sp.png

Descrição

Mapa temático mostrando cada região administrativa com cores distintas. Tamanho dos círculos proporcional ao número de óbitos, com rótulos de bairros e contagens.

Esquema de Cores

Leste      → #d32f2f (Vermelho escuro)   │ 169 óbitos (24,0%)
Centro     → #f57c00 (Laranja)           │ 147 óbitos (20,9%)
Norte      → #fbc02d (Amarelo)           │ 124 óbitos (17,6%)
Oeste      → #7cb342 (Verde)             │ 121 óbitos (17,2%)
Sul        → #0288d1 (Azul)              │ 93 óbitos (13,2%)
Sudeste    → #7b1fa2 (Roxo)              │ 49 óbitos (7,0%)

Características


✅ Cores por região: fácil identificação
✅ Tamanho proporcional: maior círculo = mais óbitos
✅ Nomes de bairros: identificação precisa
✅ Legenda: resumo por região
✅ Grid de referência: facilita localização


Achados Principais


Leste: maior carga absoluta (24% dos óbitos)
Centro: segunda maior região afetada (20,9%)
Sudeste: menor impacto relativo (7%)
Distribuição não uniforme: sugere fatores epidemiológicos específicos



📈 Análise Epidemiológica

Padrões Espaciais

Concentração Leste

A região Leste de São Paulo concentra 24% de todos os óbitos (169 casos). Bairros como Itaquera, São Miguel Paulista e Ermelino Maranhão apresentam os maiores números absolutos, refletindo a maior população e densidade demográfica da região.

Distribuição Centro-Leste

As regiões Centro e Leste juntas representam 44,9% da carga total de óbitos, indicando que a zona leste da metrópole concentra risco epidemiológico desproporcionalmente alto.

Gradiente Oeste-Sul

Regiões mais a oeste e sul apresentam concentrações menores, possivelmente relacionadas a:


Menor população em risco
Melhor acesso a água/saneamento
Diferentes padrões de contato com animais reservatórios


Hospedeiros e Transmissão

Cães como hospedeiros-ponte: 70,1% dos isolados foram obtidos de cães, sugerindo que:


Circulação urbana de Leptospira em populações caninas
Transmissão frequente para humanos (contato com urina)
Potencial para intervenção: programas de vacinação canina


Sazonalidade

Dados epidemiológicos (não mostrados nos mapas, mas documentados) indicam:


Picos: janeiro-março, maio-junho (estação chuvosa)
Mecanismo: enchentes facilitam contaminação ambiental
Mínimo: julho-agosto (seco)
Esta sazonalidade é consistente entre todas as regiões



💻 Dados Estruturados

Arquivo CSV

Arquivo: dados_completos_bairros_sp.csv

Estrutura

Bairro,Latitude,Longitude,Obitos,Regiao
Itaquera,-23.507,-46.403,25,Leste
São Miguel Paulista,-23.480,-46.415,22,Leste
...

Colunas

ColunaTipoExemploDescriçãoBairrotexto"Itaquera"Nome do bairroLatitudedecimal-23.507Coordenada Y (WGS84)Longitudedecimal-46.403Coordenada X (WGS84)Obitosinteiro25Contagem de óbitosRegiaotexto"Leste"Região administrativa

Usos


Importar em GIS (QGIS, ArcGIS)
Análises em R/Python
Criar visualizações personalizadas
Geocodificação adicional
Análises espaciais



🔍 Interpretação dos Mapas

O que buscar no heatmap

✅ Hotspots (Regiões Quentes)


Áreas em vermelho/laranja escuro
Indicam concentração elevada de óbitos
Leste é o principal hotspot


✅ Gradientes


Transição de cores mostra mudança gradual de risco
Não há fronteiras abruptas (dados interpolados)
Sugere difusão espacial do risco


✅ Vazios


Áreas em amarelo claro/branco
Baixa incidência
Sudeste é a área com menor concentração


Limitações dos Mapas

⚠️ Dados agregados: cada bairro como unidade única


Pode mascarar heterogeneidade dentro do bairro
Efeito MAUP (Modifiable Areal Unit Problem)


⚠️ Período longo (19 anos)


Agregação pode ocultar variações temporais
Padrões podem ter mudado ao longo do tempo


⚠️ Só São Paulo Capital


Não inclui região metropolitana
Comparação com litoral não cartografada


⚠️ Dados moleculares limitados


Apenas 67 isolados sequenciados
Representação enviesada?



📚 Fontes de Dados

SINAN (Sistema de Informação de Agravos de Notificação)


Organismo: Ministério da Saúde do Brasil
Plataforma: DataSUS
Período: 2007-2025
Dados: notificações obrigatórias de leptospirose confirmada
Acesso: http://www2.datasus.gov.br/


Dados Moleculares

Di Azevedo, M.A. & Lilenbaum, W. et al. (2025)


Artigo: "Molecular Epidemiology of Leptospirosis in São Paulo, Brazil"
Revista: Acta Tropica, 271:107895
DOI: [a ser atualizado]
n = 67 isolados sequenciados de São Paulo Capital
Inclui: espécies, sorogrupos, hospedeiros, paisagem



🛠️ Ferramentas Utilizadas

Python Libraries

pythonfolium==0.14.0          # Mapas interativos
folium.plugins          # Heatmap plugin
pandas==2.0.3           # Manipulação de dados
numpy==1.24.3           # Operações numéricas
matplotlib==3.7.2       # Visualizações estáticas
seaborn==0.12.2         # Heatmaps avançados
scipy==1.11.2           # Interpolação (griddata)

Processos de Análise


Limpeza de dados: remoção de valores ausentes, validação de coordenadas
Agregação: agrupamento por bairro e região
Interpolação: griddata com método cúbico (suavização)
Visualização: folium para interativo, matplotlib para estático
Validação: verificação de somas, cruzamento com dados SINAN



📖 Como Citar

Se você usar estes mapas em trabalho acadêmico ou científico, cite como:

Formato APA

[Autor], [Ano]. Mapas Heatmap de Distribuição de Leptospirose 
em São Paulo Capital, 2007-2025. [Repositório GitHub]. 
Disponível em: [URL do repositório]

Formato BibTeX

bibtex@misc{heatmap_lepto_sp_2026,
  title={Mapas Heatmap: Distribuição de Leptospirose em São Paulo},
  year={2026},
  note={Análise epidemiológica espacial integrada com dados moleculares}
}


📞 Informações de Contato

Para questões sobre os dados, análises ou mapas:


Orientador: Dr. Hélio Junji Shimozako (ESIB)
Instituição: Escola Superior do Instituto Butantan
Período: 2007-2025
Análise realizada: 2026



📝 Licença

Estes mapas e análises são fornecidos para fins educacionais e de pesquisa.


✅ Uso em trabalhos acadêmicos
✅ Compartilhamento com atribuição
⚠️ Verifique restrições de dados SINAN para uso comercial



🔄 Versões

VersãoDataAlterações1.02026Versão inicial com 4 tipos de mapas---


📎 Arquivos Inclusos

├── mapa_heatmap_sp_completo.html          # Mapa interativo Folium
├── heatmap_interpolado_sp.png             # Contour plot (300 dpi)
├── hexbin_heatmap_sp.png                  # Agregação hexagonal
├── mapa_regioes_sp.png                    # Mapa por regiões
├── dados_completos_bairros_sp.csv         # Dados estruturados
└── HEATMAP_README.md                      # Este arquivo


Desenvolvido para: TCC (Trabalho de Conclusão de Curso)

Instituição: Escola Superior do Instituto Butantan (ESIB)

Orientador: Dr. Hélio Junji Shimozako

Tema: Epidemiologia de Leptospirose em São Paulo
