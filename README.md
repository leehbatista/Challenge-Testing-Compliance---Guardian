# EnerGenius Acessível – Plano de Testes Manuais e Automatizados
### Projeto integrante do sistema Guardian – Bem-Estar Financeiro
**Equipe:** Leticia Fontana Baptista – RM 550289
Julia Palomari – RM 551910
Julia Ortiz – RM 550204
Vinicius Sobreira – RM 97767
Guilherme Catelli – RM 97989  
**Curso:** Engenharia de Software – FIAP  
**Ferramentas:** Azure DevOps Boards | Selenium IDE | GitHub  

---

## Objetivo Geral
Garantir a qualidade e estabilidade do sistema **EnerGenius Acessível**, que oferece suporte inteligente e acessível a pessoas com deficiência durante quedas de energia, por meio de testes manuais e automatizados.

---

## Parte A – Plano de Testes Manuais (Azure Boards)

### Descrição
O plano de testes foi desenvolvido na plataforma **Azure DevOps – Test Plans**, cobrindo as principais funcionalidades do sistema.  
Foram criados **6 casos de teste** com dados de entrada controlados, resultados esperados e rastreabilidade com os PBIs do backlog.

### Casos de Teste Manuais
| ID | Funcionalidade | Resultado Esperado |
|----|----------------|--------------------|
| TC01 | Cadastro de Usuário | Mensagem “Cadastro realizado com sucesso” e registro no banco de dados |
| TC02 | Login de Usuário | Login bem-sucedido e redirecionamento ao painel |
| TC03 | Registro de Dispositivo Bluetooth | Mensagem “Dispositivo adicionado com sucesso” |
| TC04 | Monitoramento de Energia | Alerta de energia disparado e log registrado |
| TC05 | Alerta Sonoro e Visual | Alerta emitido e evento registrado |
| TC06 | Painel de Controle | Dados exibidos corretamente em tempo real |

**Link para o Azure Boards:**  
https://dev.azure.com/RM550289/Guardian%20-%20Bem%20Estar%20Financeiro/_workitems/recentlyupdated/

**Documento de apoio:**  


---

## Parte B – Automação de Testes (Selenium IDE)

### Casos Automatizados
Foram automatizados 4 fluxos principais utilizando o **Postman**
Cada fluxo foi gravado simulando ações reais de um usuário.

  
### Estrutura de Repositório

/manual/
link_AzureBoards.txt
/automation/
/selenium/
AT01_Cadastro.side
AT02_Login.side
AT03_Dispositivo.side
AT04_Painel.side
/docs/
evidencias/
print_testplan.png
video_link.txt
Plano_de_Testes_Manuais_Guardian.docx
Parte_B_Automacao_EnerGenius.docx
README.md



---

## Evidências
-  **Vídeo da execução dos testes automatizados:**  
  https://youtu.be/n5QPvFDn4qU?feature=shared

---

## ✅ Checklist de Entrega
| Item | Status |
|------|---------|
| Plano de Testes Manuais no Azure Boards | ✅ |
| 6 Casos de Teste com dados controlados | ✅ |
| Test Plan e Suites configuradas | ✅ |
| 4 Testes Automatizados (Postman) | ✅ |
| Vídeo de execução gravado e linkado | ✅ |
| Repositório público com branch `develop` | ✅ |
| Documentos de apoio anexados | ✅ |

---

## Conclusão
A execução deste plano de testes garante que as funcionalidades críticas do **EnerGenius Acessível** foram validadas de forma sistemática e profissional.  
A combinação entre **Azure Boards** (testes manuais) e **Postman** (testes automatizados) assegura a qualidade do software e reforça as boas práticas de **DevSecOps e QA ágil**.
