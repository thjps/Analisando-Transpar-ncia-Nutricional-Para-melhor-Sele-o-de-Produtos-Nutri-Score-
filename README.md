<div align="center">

# Analisando Transparência Nutricional
### Melhor Seleção de Produtos (Nutri-Score)

<img src="https://github.com/user-attachments/assets/8aedce9b-e85f-4a6a-ba76-9c8fdc2414c1" width="400" alt="Nutri-Score">

**Este projeto nasceu de uma inquietação pessoal: será que as nossas escolhas no supermercado são baseadas em factos ou em marketing?**

Utilizando a base de dados do **Open Food Facts**, analisei milhares de produtos em Portugal através de **SQL (Google BigQuery)** para encontrar padrões de qualidade e as "armadilhas" nos rótulos. O objetivo foi substituir a percepção pela evidência.

---

</div>

## 🔍 Principais Descobertas (Os 5 Pilares)

### 1. 🏷️ O Mito das Marcas Próprias (MDD)
Derrubei o preconceito de que o "mais barato" é nutricionalmente pior. Dados de marcas como **Pingo Doce, Continente e Lidl** mostraram equivalência quase total às marcas líderes em açúcar e proteína. Escolher a marca do supermercado é uma poupança inteligente sem perda nutricional.

### 2. ⚡ A "Bomba" Oculta: Snacks e Marketing
Identifiquei que **83% das barras de cereais** (vendidas como "fit") são autênticas bombas de açúcar (>15g/100g). Nos sumos, o processamento elimina quase toda a fibra, deixando apenas a absorção rápida de açúcar.

### 3. 💪 Eficiência Proteica: Onde está o "Músculo"?
Criei uma métrica de **Densidade Proteica** (Proteína por 100kcal):
*   **Vencedores:** Peixes e Marisco (13g de proteína/100kcal).
*   **Destaque:** Laticínios proteicos de Marca Própria são o segmento com melhor custo-benefício.

### 4. 🧂 O Desafio do Sal em Portugal
O sal é o "inimigo invisível". No setor da panificação, **4 em cada 10 pães** excedem o limite de 1.0g de sal. O excesso de sódio no pão de prateleira é um padrão e não uma exceção.

### 5. 🏗️ O Vazio dos "Ultraprocessados"
Provada a correlação direta entre processamento e degradação: enquanto produtos simples têm <2g de açúcar, o ultraprocessado médio em Portugal ultrapassa os **20g** (um aumento de 1000%).

---

## 💡 Conclusão Geral
A transparência ainda não é a regra. O consumidor português precisa de olhar menos para a frente da embalagem e mais para a tabela traseira. Com **SQL e visão crítica**, transformamos tabelas complexas em decisões de compra mais saudáveis e económicas.
