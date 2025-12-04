# 📊 Simulador de Investimentos em Fundos Imobiliários

## 📌 Descrição
Este projeto é uma planilha em Excel desenvolvida para simular investimentos em **Fundos Imobiliários (FIIs)**.  
A ferramenta permite calcular o patrimônio acumulado e os dividendos mensais ao longo do tempo, ajudando o investidor a tomar decisões mais informadas.

---

## ⚙️ Configurações Iniciais
- **Salário:** R$ 2.000,00  
- **Rendimento da Carteira:** 0,60%  
- **Sugestão de Investimento (30% do salário):** R$ 600,00  

---

## 💰 Investimento Mensal
- **Valor investido por mês:** R$ 200,00  
- **Prazo:** 5 anos  
- **Taxa de rendimento mensal:** 1,08%  
- **Patrimônio acumulado ao final:** R$ 16.755,38  
- **Dividendos mensais estimados:** R$ 100,53  

---

## 📈 Cenários de Crescimento
A planilha simula diferentes horizontes de tempo:

| Prazo (anos) | Patrimônio acumulado | Dividendos mensais |
|--------------|----------------------|--------------------|
| 2            | R$ 5.445,53          | R$ 32,67           |
| 5            | R$ 16.755,38         | R$ 100,53          |
| 10           | R$ 48.656,84         | R$ 291,94          |
| 20           | R$ 225.039,68        | R$ 1.350,24        |
| 30           | R$ 864.433,93        | R$ 5.186,60        |

---

## 🧑‍💼 Perfil do Investidor
- **Perfil:** Moderado  
- **Valor mensal investido:** R$ 200,00  

---

## 🏢 Alocação Sugerida em FIIs
Distribuição recomendada dos aportes mensais:

| Tipo de FII       | Percentual | Valor mensal |
|-------------------|------------|--------------|
| Papel             | 32%        | R$ 64,00     |
| Tijolo            | 35%        | R$ 70,00     |
| Híbridos          | 8%         | R$ 16,00     |
| FOFs              | 5%         | R$ 10,00     |
| Desenvolvimento   | 10%        | R$ 20,00     |
| Hotelarias        | 10%        | R$ 20,00     |
| **Total**         | 100%       | R$ 200,00    |

---

## 🛠️ Lógica da Planilha
1. **Entrada de dados:** salário, valor mensal investido, taxa de rendimento e prazo.  
2. **Cálculo do patrimônio acumulado:**  
   - Fórmula base: `FV = PMT * (((1+i)^n - 1) / i)`  
   - Onde:  
     - `PMT` = aporte mensal  
     - `i` = taxa de rendimento mensal  
     - `n` = número de meses  
3. **Cálculo dos dividendos mensais:**  
   - Dividendos = Patrimônio acumulado × Rendimento da carteira  
4. **Simulação de cenários:** diferentes prazos (2, 5, 10, 20, 30 anos).  
5. **Distribuição dos aportes:** valores mensais alocados conforme percentual sugerido por tipo de FII.

---

## 📂 Estrutura do Repositório
- `Simulador_Investimentos.xlsx` → Planilha principal  
- `README.md` → Documentação detalhada  
- `/images` → Capturas de tela ilustrativas  

---

## 👨‍💻 Autor
Projeto desenvolvido como parte do desafio da DIO.
