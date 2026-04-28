# solucoes-freelancer

Repositório dedicado ao desenvolvimento de soluções reais de negócio utilizando **Java** e **Programação Orientada a Objetos**. O diferencial deste projeto é a implementação de **Security by Design**, aplicando camadas de defesa contra inputs maliciosos diretamente nos objetos.
## 📈 Progresso das Soluções
| Projeto | Tema | Nível | Status |
|---|---|---|---|
| 01 | Clínica Veterinária (Gestão) | 🟢 Fácil | ⏳ Pendente |
| 02 | projeto_oficina.Oficina Mecânica (Ordens) | 🟢 Fácil | ⏳ Pendente |
| 03 | Pet Shop (Fichas Pet) | 🟢 Fácil | ⏳ Pendente |
| 04 | Loja de Colecionáveis (Itens) | 🟡 Médio | ⏳ Pendente |
| 05 | Consultório Odonto (Procedimentos) | 🟡 Médio | ⏳ Pendente |
| 06 | Barbearia (Agendamentos) | 🟡 Médio | ⏳ Pendente |
| 07 | Academia de Judô 🥋 (Matrículas) | 🔴 Difícil | ⏳ Pendente |
| 08 | Torneio E-Sports (Inscrições) | 🔴 Difícil | ⏳ Pendente |
## 🔐 Camada de Cibersegurança (Cyber-POO)
Diferente de sistemas comuns, cada classe aqui é blindada contra ataques básicos:
* [ ] **Anti-XSS**: Bloqueio de tags <script> e caracteres < > nos setters de texto.
* [ ] **Sanitização de Input**: Filtro de caracteres especiais que podem causar quebras de lógica.
* [ ] **Integridade Numérica**: Validação de intervalos (ex: impedir valores negativos).
* [ ] **Encapsulamento Estrito**: Uso rigoroso de private para impedir estados inválidos.
* [ ] **Return Early**: Implementação de validações que interrompem a execução antes do erro.
## 🧠 Conceitos Praticados
* [ ] **Membros Estáticos**: Controle de protocolos e IDs automáticos via static.
* [ ] **Sobrecarga**: Múltiplos construtores utilizando this().
* [ ] **Vetores de Objetos**: Gestão de frota, pacientes e clientes em memória.
* [ ] **Lógica de Ordenação**: Implementação manual de algoritmos como Bubble Sort.
## 🚀 Como Executar
Os projetos estão organizados em pastas por nível de dificuldade:
```bash
# Exemplo para rodar o Projeto 01
javac facil/projeto01_clinica_veterinaria/*.java
java facil.projeto01_clinica_veterinaria.projeto_clinica.DemoConsulta

```
## 👤 Autor
**Cauê** | *Desenvolvedor Backend & Pesquisador de Cibersegurança* **IFCE - Campus Maracanaú**