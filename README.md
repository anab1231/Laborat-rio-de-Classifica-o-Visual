 Para documentar este experimento de **IA Ética** no seu GitHub, preparei um resumo estruturado que destaca a sua capacidade de identificar falhas críticas em sistemas de aprendizado de máquina e propor soluções humanizadas.

---

# ⚖️ Laboratório: Viés Algorítmico e Ética em IA

Este repositório registra um experimento prático de **Classificação Visual** utilizando o *Teachable Machine* (Google), com o objetivo de demonstrar como bases de dados enviesadas geram sistemas discriminatórios e tecnicamente falhos.

## 🧪 Parte 1: O Experimento Técnico

O modelo foi treinado para classificar indivíduos entre "Perfil Liderança" e "Perfil Operacional" utilizando um **dataset deliberadamente corrompido** para observar o comportamento da IA.

### **Metodologia de Treinamento**
* **Classe A (Perfil Liderança):** Alimentada exclusivamente com imagens seguindo estereótipos de gênero e vestimenta formal (ex: homens de terno).
* **Classe B (Perfil Operacional):** Alimentada com imagens informais ou perfis que fogem ao padrão da Classe A.
* **Resultado:** O modelo cria uma correlação falsa onde "Liderança" é definida por roupas e gênero, e não por competência.

### **Registro da Falha (Erro de Inferência)**
Ao apresentar ao modelo um indivíduo que não se encaixa nos padrões estereotipados (ex: uma mulher em posição de comando ou um homem de terno em contexto informal), o sistema apresenta um **Falso Negativo** ou classificação incorreta, comprovando a incapacidade da IA de generalizar além do viés inserido.

---

## 📝 Parte 2: Memorial de Impacto e Ética

Respostas analíticas sobre o impacto humano da tecnologia:

### **Mecanismo do Viés**
A seleção restrita de dados **corrompe** a lógica do algoritmo porque ele **limita** o aprendizado a padrões superficiais e estatisticamente pobres. O sistema **reproduz** o preconceito humano como se fosse uma verdade matemática, **gerando** uma visão distorcida que **ignora** a diversidade da realidade e **valida** exclusões históricas através de uma máscara de neutralidade tecnológica.

### **Consequência Social**
O sistema **marginaliza** o indivíduo ao **negar** sua identidade e potencial profissional, **causando** um profundo desgaste emocional e invisibilidade. Essa classificação **interfere** diretamente no acesso a oportunidades e **reforça** barreiras sistêmicas, **colocando** o profissional em uma posição de constante desvantagem e injustiça institucionalizada.

### **Ação Mitigadora (Human-in-the-loop)**
Uma intervenção eficaz **garante** a equidade através de um comitê de curadoria diverso que **revisa** e **audita** o dataset antes do treinamento. Esse processo **inclui** a busca ativa por dados representativos e **implementa** testes de estresse para identificar vieses, **assegurando** que a decisão final sempre **tenha** supervisão humana crítica para corrigir distorções automatizadas.

---

## 🔧 Como foi realizado
1.  **Coleta de Dados:** Utilização da câmera e upload de imagens para criar categorias baseadas em estereótipos.
2.  **Treinamento:** Processamento via *Teachable Machine* para gerar o modelo de classificação.
3.  **Teste de Stress:** Exposição do modelo a casos reais fora do padrão de treinamento para capturar a falha de classificação.
4.  **Reflexão Ética:** Análise técnica sobre como os dados impactam a vida real.

---
*Atividade realizada para a disciplina de Inteligência Artificial e Sociedade - 2026.*



