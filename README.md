# Painel de Acompanhamento do Sistec – IFFar

Este repositório contém o **Painel de Acompanhamento do Sistec**, uma ferramenta institucional desenvolvida para apoiar o monitoramento, a análise e a qualificação dos dados acadêmicos registrados no Sistema Nacional de Informações da Educação Profissional e Tecnológica (Sistec), no âmbito do Instituto Federal Farroupilha (IFFar).

O painel foi desenvolvido em Power BI, com as linguagens Dax e M, seguindo boas práticas de versionamento por meio do Power BI Project (PBIP), garantindo organização, rastreabilidade e evolução contínua do projeto.

---

## 🎯 Objetivo

Disponibilizar um painel interativo que permita:

- Consolidar dados de matrículas registradas no Sistec;
- Acompanhar a situação acadêmica dos estudantes;
- Simular indicadores institucionais alinhados à **Plataforma Nilo Peçanha (PNP)**;
- Antever inconsistências e necessidades de ajuste nos dados antes do ciclo oficial de validação da PNP;
- Apoiar a gestão acadêmica e o planejamento institucional.

---

## 📊 Evolução do Painel

- **Versão anterior**  
  Apresentava exclusivamente o quantitativo de matrículas com situação “em curso” conforme registros do Sistec.

- **Versão atual**  
  Incorpora a **simulação de indicadores da PNP**, calculados diretamente a partir dos dados do Sistec, ampliando a capacidade analítica e estratégica do painel.

---

## 📈 Indicadores Simulados

O painel disponibiliza a simulação dos seguintes indicadores institucionais:

- Eficiência Acadêmica
- Taxa de Evasão
- Percentuais Legais

Esses indicadores funcionam como uma prévia analítica, auxiliando as unidades a identificar possíveis ajustes necessários antes do período oficial de validação da PNP, usualmente em fevereiro de cada ano.

> ⚠️ **Observação**  
> Os cálculos seguem as regras vigentes da PNP, mas são apenas prévias, visto que os dados podem ser alterados durante o ciclo da PNP. Portanto, não substituem os resultados oficiais publicados pela plataforma.

---

## 🔍 Funcionalidades do Painel

Ao acessar o painel, é possível:

- Alternar visualizações por:
  - Campus
  - Tipo de curso
  - Modalidade
  - Curso específico

- Utilizar filtros combinados para análises detalhadas, como:
  - Cursos com matrículas ativas em determinado ano;
  - Ingressantes de um ano específico que evadiram no mesmo período;

- Verificar se os dados registrados no Sistec refletem a realidade institucional.


---

## 🛠️ Tecnologias Utilizadas

- **Power BI Desktop**
- **Power BI Project (PBIP)**
- **Git / GitHub** para versionamento
- Linguagens:
  - DAX
  - Power Query (M)

---

## 📍 Disponibilização Institucional

O painel está disponível no site do IFFar, no caminho:

Desenvolvimento Institucional > Planejamento e Desenvolvimento Institucional > Painéis e Publicações > Acompanhamento Sistec
[ACESSE O PAINEL](https://www.iffarroupilha.edu.br/planejamento-e-desenvolvimento/blog_dpdi/item/38819-painelsistec) para mais detalhes.

---

## Licença

Este projeto é um software proprietário de **uso não comercial**.

✔ Uso institucional, acadêmico e educacional permitido  
❌ Uso comercial, venda ou sublicenciamento **não permitido**

Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
