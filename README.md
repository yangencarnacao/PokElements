# ⚛️ PokéQuímica: A Batalha dos Elementos

> Um jogo educativo interativo desenvolvido em HTML5, CSS3 e JavaScript puro, inspirado na dinâmica de cartas colecionáveis e na Tabela Periódica.

---

## 📖 Sobre o Projeto

O **PokéQuímica** transforma o estudo dos elementos químicos numa experiência interativa e lúdica. Baseado em baralhos colecionáveis temáticos divididos pelos blocos da Tabela Periódica (**S**, **P**, **D** e **F**), o projeto integra mecânicas clássicas de *Super Trunfo*, adivinhações de silhuetas e montagem de tabuleiro.

O jogo funciona inteiramente no navegador através de um único ficheiro independente, sem dependência de bibliotecas externas ou ligações que possam expirar.

---

## 🎮 Modos de Jogo

### 1. Elementodéx (Coleção de Cartas)

* Visualização com efeito holográfico de todas as cartas do jogo.
* Filtros dinâmicos por Bloco:
* **Bloco S**: Metais Alcalinos e Alcalino-terrosos.


* **Bloco P**: Não Metais e Metais Representativos.


* **Bloco D**: Metais de Transição.


* **Bloco F**: Lantanídeos e Actinídeos (Terras Raras e Radioativos).




* Janela de detalhes com lista completa de propriedades físico-químicas e curiosidades de cada elemento.



### 2. Batalha Super Trunfo

* Duelo por turnos contra a inteligência artificial do **Dr. Rutherford**.
* Escolha de atributos estratégicos a cada ronda:
* Número Atómico ($Z$)


* Poder Químico
* Reatividade
* Densidade


* Feedback visual de vitória, empate ou derrota com cálculo de pontuação contínua.

### 3. Tabela Puzzle (Encaixe Periódico)

* Desafio de localização baseado no esquema estrutural da Tabela Periódica.


* O jogador deve analisar a carta sorteada e posicioná-la no bloco e grupo correspondentes.

### 4. Quem é esse Pokémon Químico? (Quiz)

* Mecânica clássica de adivinhação através de silhuetas escuras.
* Revelação progressiva de 3 pistas baseadas nas propriedades do elemento químico.


* Opções de múltipla escolha com temporizador e pontuação por precisão.

---

## 🧪 Elementos Incluídos

| Bloco | Elementos Catalogados |
| --- | --- |
| **Bloco D**

 | Ferro ($Fe$), Cobre ($Cu$), Zinco ($Zn$), Níquel ($Ni$), Cromo ($Cr$)

 |
| **Bloco S**

 | Lítio ($Li$), Sódio ($Na$), Potássio ($K$), Magnésio ($Mg$), Cálcio ($Ca$)

 |
| **Bloco P**

 | Carbono ($C$), Nitrogénio ($N$), Oxigénio ($O$), Alumínio ($Al$), Cloro ($Cl$)

 |
| **Bloco F**

 | Cério ($Ce$), Neodímio ($Nd$), Tório ($Th$), Urânio ($U$), Plutónio ($Pu$)

 |

---

## 🛠️ Tecnologias Utilizadas

* **HTML5**: Estruturação semântica de interfaces, janelas modais e grelhas da tabela periódica.
* **CSS3**:
* Animações com `transform: rotateY()` para efeito de cartas em 3D.
* Efeitos holográficos via gradientes radiais e `backdrop-filter`.
* Layout responsivo estruturado em CSS Grid e Flexbox.


* **JavaScript (ES6+)**:
* Gestão de estado do jogo, baralhos e rondas de batalha.
* Renderização dinâmica de cartas a partir de um array estruturado de objetos.


* **Web Audio API**:
* Sintetizador de efeitos sonoros nativo (sem recurso a ficheiros `.mp3` ou `.wav` externos).



---

## 🚀 Como Executar o Projeto

Como o jogo foi concebido num ficheiro autocontido, não é necessária a instalação de dependências, servidores ou compiladores.

1. Faça o clone deste repositório:
```bash
git clone https://github.com/seu-usuario/poke-quimica.git

```


2. Navegue até ao diretório do projeto:
```bash
cd poke-quimica

```


3. Abra o ficheiro `index.html` em qualquer navegador web moderno (Chrome, Firefox, Safari, Edge):
```bash
# No macOS
open index.html

# No Linux
xdg-open index.html

# No Windows
start index.html

```



---

## 🎯 Aplicação Pedagógica

Este projeto foi desenhado para ser utilizado em salas de aula de Ciências e Química (Ensino Básico e Secundário), auxiliando na fixação de:

* Estrutura e divisões da Tabela Periódica (blocos $s$, $p$, $d$, $f$, famílias e períodos).


* Noções de massa atómica, número atómico e propriedades periódicas (raio atómico, afinidade e reatividade).


* Aplicações reais dos elementos químicos no quotidiano e na indústria moderna.



---

## 📄 Licença

Este projeto está sob a licença [MIT](https://www.google.com/search?q=LICENSE). Consulte o ficheiro de licença para mais detalhes.
