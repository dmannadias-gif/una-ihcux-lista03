# ScannerExpert – Simulador de Deep Scan

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte da **Missão 03 – Operação Deep Scan**, da disciplina de **IHC/UX**.

O objetivo é criar um **simulador de varredura de sistema no terminal**, mostrando ao usuário o progresso das tarefas em tempo real.

O programa utiliza mensagens de status como:

* Verificando CPU
* Lendo Memória RAM
* Sincronizando SDK
* Validando Permissões
* Finalizando

Cada etapa é exibida no terminal enquanto o sistema simula o processamento.

---

## 🎯 Heurística Aplicada

Este projeto aplica a **1ª Heurística de Nielsen: Visibilidade do Status do Sistema**.

Essa heurística afirma que **o sistema deve sempre manter o usuário informado sobre o que está acontecendo**, fornecendo feedback claro e em tempo razoável.

No código, isso é implementado através de:

* Mensagens de progresso exibidas no terminal
* Atualização da linha com `[PROCESSANDO]`
* Simulação de tempo de execução com `Thread.Sleep()`

Dessa forma, o usuário consegue acompanhar o andamento da tarefa e não fica com a impressão de que o programa travou.

---

## 🖥️ Tecnologias Utilizadas

* C#
* .NET Console Application
* Visual Studio Code
* Terminal

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:

```
git clone https://github.com/seu-usuario/una-ihcux-lista03.git
```

2. Entre na pasta do projeto:

```
cd ScannerExpert
```

3. Execute o programa:

```
dotnet run
```

---

## 📸 Evidência de Execução

O arquivo **minha-evidencia.png** mostra o momento em que o sistema está executando a análise, exibindo a mensagem `[PROCESSANDO]`, demonstrando a aplicação da heurística de **Visibilidade do Status do Sistema**.

Projeto desenvolvido para atividade acadêmica de **Interação Humano-Computador (IHC)**.
