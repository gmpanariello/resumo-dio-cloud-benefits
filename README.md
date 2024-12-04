# Resumo DIO Cloud Benefits

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do laboratório no módulo "Benefícios da Computação em Nuvem" da DIO.

O objetivo principal do módulo foi explorar os benefícios da computação em nuvem, especificamente no Azure, e entender como esses recursos podem agregar valor aos negócios. A seguir, trago um resumo das minhas anotações com base nas explicações da professora Valéria Baptista.

---

## **Benefícios da Nuvem Azure**

### **1. Alta Disponibilidade**
- Garante que os sistemas estejam sempre funcionando e acessíveis aos usuários.  
- Recursos ficam disponíveis sempre que necessário.  
- Em caso de indisponibilidade, o usuário pode receber “créditos” como compensação.  

### **2. Escalabilidade**
- Capacidade de ajustar recursos de acordo com a demanda.  
- Modelo baseado em consumo: paga-se apenas pelo que é usado.  
- Permite:
  - **Escala vertical:** adicionar mais CPUs ou RAM a uma máquina virtual.  
  - **Escala horizontal:** aumentar o número de instâncias para distribuir a carga.

### **3. Elasticidade**
- Ideal para eventos de alta demanda, como a "Black Friday".  
- Permite expandir ou reduzir automaticamente os recursos conforme necessário.  
- Exemplo prático: configuração automática para adicionar servidores ao atingir determinado nível de processamento, e removê-los quando a demanda diminuir.

### **4. Confiabilidade**
- Design descentralizado, com suporte a múltiplas regiões, aumentando a resiliência.  
- Sistemas continuam funcionando mesmo em caso de falhas ou eventos catastróficos em uma região.  

### **5. Previsibilidade**
- Permite confiança no desempenho e nos custos.  
- Baseado no **Microsoft Azure Well-Architected Framework**, ajuda a planejar e implementar soluções de forma eficiente.  

### **6. Segurança**
- Oferece ferramentas avançadas, mas muitas delas precisam ser configuradas pelo cliente.  
- Modelos:
  - **Infraestrutura como Serviço (IaaS):** controle total do cliente.  
  - **Plataforma como Serviço (PaaS) e Software como Serviço (SaaS):** maior automação em patches e manutenção.  
- Ajuda a proteger sistemas contra ataques internos e externos.  

### **7. Governança**
- Permite gerenciar recursos de acordo com padrões específicos, como os exigidos em setores regulados (ex.: farmacêutico).  
- Auditorias automáticas ajudam a manter conformidade e aplicar estratégias de mitigação.  
- Regras podem ser personalizadas para atender necessidades corporativas.  

### **8. Gerenciabilidade**
- Oferece diversas formas de gerenciar os recursos:
  - **Na nuvem:** configurações automáticas e escalabilidade de recursos.  
  - **Do ambiente:** via portal web, linha de comando, APIs ou PowerShell.  

---

## **Acordos de Nível de Serviço (SLA)**

### **O que significa SLA?**

Os **SLAs (Service Level Agreements)** definem o compromisso do provedor de nuvem com a entrega de serviços dentro de parâmetros específicos, como tempo de disponibilidade garantido. Por exemplo, um SLA de 99,9% significa que o serviço pode ficar indisponível por até 43,2 minutos em um mês.  

A tabela abaixo exemplifica o impacto de diferentes níveis de disponibilidade em períodos de tempo:

| Disponibilidade | Não Conformidade por Semana | Não Conformidade por Mês | Não Conformidade por Ano |
|------------------|-----------------------------|---------------------------|---------------------------|
| **99%**         | 1,68 horas                 | 7,20 horas               | 3,65 dias                |
| **99,9%**       | 10,10 minutos              | 43,20 minutos            | 8,76 horas               |
| **99,95%**      | 5 minutos                  | 21,60 minutos            | 4,38 horas               |
| **99,99%**      | 1,01 minuto                | 4,32 minutos             | 52,56 minutos            |
| **99,999%**     | 6 segundos                 | 25,90 segundos           | 5,26 minutos             |



---

Este módulo foi essencial para ampliar minha compreensão sobre os benefícios da computação em nuvem, proporcionando um entendimento mais claro de conceitos como alta disponibilidade, escalabilidade, elasticidade, confiabilidade, previsibilidade, segurança, governança e gerenciabilidade. Aprender sobre essas características me preparou melhor para identificar e aplicar soluções tecnológicas eficazes no futuro. Além disso, o desafio de resumir meu aprendizado neste projeto permitiu consolidar os conceitos apresentados, revisitar pontos-chave e refletir sobre como esses benefícios podem ser aplicados em diferentes contextos, reforçando ainda mais meu conhecimento.

