# 🎣 Phishing: Simulação de Captura de Credenciais do Facebook

> 🛡️ **Objetivo do laboratório:** compreender como ataques de phishing podem utilizar páginas falsas para enganar usuários e como identificar os riscos envolvidos nesse tipo de ameaça.
>
> ⚠️ **Aviso de segurança:** execute os testes somente em um ambiente controlado, com autorização explícita. Não utilize contas reais nem colete, armazene ou compartilhe senhas de terceiros.

---

## 🧰 1. Ferramentas utilizadas

As ferramentas abaixo compõem o ambiente de laboratório para estudo de engenharia social.

| Ferramenta | Descrição |
|---|---|
| 🐉 Kali Linux | Distribuição Linux voltada a testes de segurança e análise de vulnerabilidades. |
| 🛠️ SEToolkit | Social-Engineer Toolkit, ferramenta utilizada para estudar e simular técnicas de engenharia social. |
| 🌐 Navegador web | Permite visualizar páginas e analisar indicadores de autenticidade. |

---

## 🧪 2. Visão geral do laboratório

O experimento demonstra o conceito de *phishing*, uma técnica de engenharia social na qual um atacante tenta convencer a vítima a acessar uma página fraudulenta e fornecer informações confidenciais.

### 🔎 Etapas conceituais

1. 🖥️ **Preparação do ambiente:** inicialização do Kali Linux e verificação das ferramentas disponíveis.
2. 🛠️ **Seleção do cenário:** identificação das funcionalidades de engenharia social do SEToolkit.
3. 🌐 **Análise da página:** observação das características visuais e dos elementos que podem tornar uma página falsa semelhante à original.
4. 🔐 **Avaliação de riscos:** identificação dos possíveis impactos da exposição de credenciais.
5. 🛡️ **Mitigação:** definição de medidas para evitar o roubo de contas e informações pessoais.

---

## ⚙️ 3. Componentes do SEToolkit

O SEToolkit possui opções voltadas à simulação de ataques de engenharia social.

| Componente | Finalidade |
|---|---|
| Social-Engineering Attacks | Agrupa recursos relacionados à engenharia social. |
| Web Site Attack Vectors | Reúne cenários de ataque baseados em páginas web. |
| Credential Harvester | Demonstra os riscos associados à captura de dados inseridos em formulários. |
| Site Cloner | Ilustra como páginas podem ser reproduzidas visualmente para simular um site legítimo. |

> ⚠️ Esses recursos podem expor credenciais reais quando utilizados indevidamente. Para fins educacionais, utilize páginas fictícias e dados de teste, sem enviar informações para serviços externos.

---

## 🖼️ 4. Evidências do laboratório

A imagem abaixo deve documentar o resultado observado durante o experimento.

![Evidência do laboratório de phishing](./passwd.png "Evidência do laboratório")

*Legenda sugerida: registro visual do resultado obtido durante a simulação em ambiente controlado.*

---

## 🚨 5. Principais riscos identificados

- 🔑 **Roubo de credenciais:** informações digitadas em páginas fraudulentas podem ser expostas.
- 👤 **Sequestro de contas:** contas comprometidas podem ser utilizadas para aplicar novos golpes.
- 💬 **Engenharia social:** mensagens convincentes podem induzir usuários a ignorar sinais de fraude.
- 🔗 **URLs fraudulentas:** endereços semelhantes aos legítimos podem dificultar a identificação do golpe.
- 🔄 **Reutilização de senhas:** uma senha comprometida pode colocar outras contas em risco.

---

## 🛡️ 6. Como se proteger

- ✅ Confira o domínio do site antes de inserir credenciais.
- 🔐 Utilize autenticação multifator, preferencialmente com passkeys ou chaves de segurança.
- 🔑 Mantenha senhas únicas para cada serviço e utilize um gerenciador de senhas confiável.
- 🚫 Não acesse páginas de login por links inesperados recebidos em mensagens.
- 📢 Denuncie páginas suspeitas e comunique possíveis incidentes aos responsáveis pela segurança.
- 🔍 Em caso de exposição, altere a senha em um dispositivo confiável, encerre sessões desconhecidas e revise os métodos de recuperação da conta.

---

## 📚 7. Conclusão

O phishing explora principalmente a confiança e a desatenção do usuário. A semelhança visual entre uma página falsa e uma página legítima pode facilitar a fraude, mas não garante que a vítima forneça suas credenciais.

A combinação de conscientização, autenticação resistente a phishing, senhas exclusivas e procedimentos de resposta a incidentes reduz significativamente os riscos.

**🎯 Aprendizado principal:** compreender a técnica é importante para reconhecer, prevenir e responder a ataques — sempre com responsabilidade e autorização.

---

*📅 Documento de laboratório — Segurança da Informação e Conscientização contra Phishing.*
