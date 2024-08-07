# Tradução do Fallout New Vegas, DLCs e Mods
Tradução do Fallout New Vegas e todas suas DLCs, pacths de correção e vários Mods.

Os arquivos .sst são dicionários do [xTranslator](nexusmods.com/skyrimspecialedition/mods/134), e precisam dele e dos arquivos originais para serem lidos.

Os ESPs e ESMs usados na tradução serão postados depois de prontos, diretamente no Nexus. Esse repositório existe apenas para me permitir acessar o dicionário de qualquer lugar, para organizar o projeto e permitir que seja usada como base para outras traduções e mods.


## Andamento da tradução
### TRADUÇÃO POSTADA!!!

- Tradução Fallout NV + DLCs: [Nexus](https://www.nexusmods.com/newvegas/mods/72771/)
- Tradução do YUP: [Nexus](https://www.nexusmods.com/newvegas/mods/72785/)
- Tradução Asterra's Many Fixes: [Nexus](https://www.nexusmods.com/newvegas/mods/72788)
- Tradução Logic and Consistency Fixes: [Nexus](https://www.nexusmods.com/newvegas/mods/72790)
- Tradução Unofficial Patch NVSE Plus: [Nexus](https://www.nexusmods.com/newvegas/mods/72791/)

Para ver os ã, vocês irão precisar do [DarNified UI](https://taleoftwowastelands.com/viewtopic.php?f=55&t=7284).
Siga as instruções na página do mod de como fazer as fontes funcionarem.

Outros mods ainda serão inclusos após a tradução do jogo completo.


# Mudanças feitas na tradução
Essas mudanças influenciam todas as outras traduções que serão feitas para esse jogo, já que essa é a base.
Pode estar faltando alguma coisa, nem tudo eu anotei.

- Algumas palavras e expressões usarão a versão em Espanhol, Italiano ou Francês, em vez do Inglês, como base para saber se deveria traduzir ou não (exemplo Dead Horses que todos traduzem e eu não tinha traduzido, mas nenhuma traduz Zion para Sião, como eu tinha traduzido), ou para ter mais de uma referência de tradução (exemplo Courier, que em todas as linguas derivadas do Latim estão com algo referente à Mensageiro, e não Entregador (como eu tinha colocado)).
O problema é que eu comecei a usar essas referências agora, então elas só contam para os termos presentes em Issues (que conta pro jogo base e dlcs) e na tradução de Lonesome Road e Gun Runner.

- Tentei corrigir alguns diálogos idiotas (baixa inteligência).
		
- Troca do nome dos marteletes (Bighorn) para Carneiro-Selvagem - [Wikipedia](https://pt.wikipedia.org/wiki/Carneiro-selvagem)
		
- Troca do nome (Bark Scorpions) para Escorpião de Casca - [Manual MSD](https://www.msdmanuals.com/pt/profissional/les%C3%B5es-intoxica%C3%A7%C3%A3o/mordidas-e-picadas/picadas-de-escorpi%C3%A3o)
			
- Correção de ações dentro de diálogos (<Minta> para <Mentir> e <Ataque> para <Atacar> e etc)
			
- Padronização de nomes (ex.: Powder Ganger tem 2 nomes dentro da tradução da GameVício - Gangue da Pólvora e Arruaceiros da Pólvora, agora é só Arruaceiros da Pólvora)
			
- Sérias dificuldades com a tradução de algumas gírias e expressões do DeadMoney (gírias antigas e específicas do local)
			
- Algumas partes da tradução podem ficar estranhas pra quem entende um pouco de inglês e entender o que o NPC está falando. Tentei ao máximo manter a coerência entre a história, emoções e o que estava sendo dito, mas priorizei o entendimento do contexto e a intenção do NPC.
			
- Correção de algumas siglas de patentes militares.
			
- Correção da tradução da Crimson Caravan (de Caravana Vermelha para Caravana Carmesim, que a tradução correta de Crimson)

- Muitas coisas em inglês são de gênero neutro, tentei corrigir e manter isso no que encontrei. (ex: "Your friends" quando mencionado os NPCs te acompanhando. Na tradução são referidos como amigos ou amigo (quando é apenas um). Foi corrigido para companhias, que é de genero neutro)

- Honey mesquite (Prosopis glandulosa) traduzido para Algaroba Mel em vez de Alcachofra de Mel - Não existe o nome em português. Algaroba (Prosopis juliflora) é outra planta, mas é considerada tradução de mesquite, provavelmente por ser o nome usado para o genero botânico (Prosopis) - [Referência](https://pt.wikipedia.org/wiki/Prosopis) - Alcachofra não faz o MENOR sentido.

- Alguns diálogos em Honest Hearts podem não estar perfeitamente traduzidos por serem passagens da bíblia. Eu preferi usar as passagens como estão na bíblia em português (NVI) em vez de uma tradução literal diretamente do inglês (Como no diálogo de Joshua sobre Sião, que na verdade ele cita parte do Salmo 137)

- Think Tank foi traduizdo para Labortatório de Ideias por ser a tradução "oficial" da expressão - [Wikipedia](https://pt.wikipedia.org/wiki/Think_tank#:~:text=Um%20think%20tank%2C%20laborat%C3%B3rio%20de,%2C%20economia%2C%20assuntos%20militares%2C%20de) 

- O Malapropismo de Mobius. Mobius aparenta ter um problema com troca de palavras por outras com sons parecidos (ex.: reason -> raisin, quite <-> quiet, desert -> dessert, etc). As vezes da pra pegar os erros, mas nem sempre. Na tradução eu mantive a intenção da palavra original (ex.: reason -> razão) e tentei, nos diálogos, colocar uma palavra parecida ainda na tentativa de manter o sentido da palavra trocada (razão -> ração | No original é trocado por raisin, que é passas, mantendo aind aum sentido de "comida" na troca das palavras). Pode ser que tenha passado algo, desculpa.

- Ainda existem outras mudanças que serão e estão sendo feitas. A tradução está em constante mudança e repadronização. As que faltam estão em Issues, no post fixado. Conforme forem sendo feitas, virão para essa lista.

## Arquivos da tradução
### fnv pt-br_en_ptbr.sst (FNV PT-BR.esm)
	
- Essa é a tradução do jogo principal mais as DLCs embutidas num único arquivo ESM. Fiz isso pois a mesclagem ajudou a resolver incompatibilidades entre FO3 e Broken Steel, então também achei que ajudaria aqui em possíveis incompatibilidades.
- O ESM também ajuda em problemas onde a tradução poderia sobrescrever alguns patches oficiais que são ESM e suas alterações. Não queremos isso.
- Para a tradução funcionar, é necessário todas as DLCs e o YUP:
  - CaravanPack.esm
  - ClassicPack.esm
  - DeadMoney.esm
  - GunRunnersArsenal.esm
  - HonestHearts.esm
  - LonesomeRoad.esm
  - MercenaryPack.esm
  - OldWorldBlues.esm
  - TribalPack.esm
  - YUP - Base Game + All DLC.esm
  - YUP - NPC Fixes (Base Game + All DLC).esp


## Créditos
  <details>
  <summary>Créditos pela tradução original da Game-Vício</summary>

| Pessoas       | Função        |
| ------------- |:-------------:|
germanio | Administrador do Projeto
x15_tiago | Co-Administrador
bRuNo_CarValhO | Co-Administrador
germanio | Tradutor
Elenildogba | Tradutor
johnsonbr | Tradutor
italopimp | Tradutor
ratumau	| Tradutor
alexcnetojr | Tradutor
braultimate | Tradutor
felipe.caputo | Tradutor
Laiton Garcia | Tradutor
Teixeiranunes | Tradutor
andxtreme | Tradutor
Binhozao	| Tradutor
Gabriel Arcanjo	| Tradutor
xhurry	| Tradutor
nandexmetal	| Tradutor
Art56	| Tradutor
Tiagus Aran |	Tradutor
ivancardosodossantos |	Tradutor
E.M.N	| Tradutor
vitordafonseca |	Tradutor
ImDead	| Tradutor
Anônimo	| Tradutor
xgabrielxal	| Tradutor
blademtr |	Tradutor
bidabida | Tradutor
lcpdeath	| Tradutor
thiagotnn	| Tradutor
Malkav	| Tradutor
Jota P	| Tradutor
Beerre	| Tradutor
Arcanwolf	| Tradutor
tiagoesanto	| Tradutor
lucjedi	| Tradutor
deliotomaz |	Tradutor
ilusaodigital	| Tradutor
rafaelpcb	| Tradutor
7hiagomp	| Tradutor
Resukyuu	| Tradutor
luisinho42	| Tradutor
Br!@N	| Tradutor
Felipe_Montalvao |	Tradutor
gui_tutilo	| Tradutor
JuryRigger	| Tradutor
brunoluizfonseca1 |	Tradutor
FMalk	| Tradutor
THENEST	| Tradutor
chris2	| Tradutor
germanio	| Revisor
ratumau	| Revisor
adriano.dt	| Revisor

</details>

- [xTranslator](nexusmods.com/skyrimspecialedition/mods/134) 
- [Lista de Siglas Militares em PT-BR](http://www.siga.arquivonacional.gov.br/images/codigos_tabelas/cctt_md_2013.pdf) 
- [Dicionário Cambridge Inglês-Português](https://dictionary.cambridge.org/pt/dicionario/ingles-portugues/) 
- [Guia dos Palavrões em Inglês - Adir Ferreira](http://www.adirferreira.com.br/wp-content/uploads/2016/12/Guia_dos_Palavroes_em_Ingles.pdf) 
- [Reverso Translation](https://www.reverso.net/)
- [Fallout Fandom](https://fallout.fandom.com/)  
- [Bíblia Online](https://www.bibliaon.com/)

