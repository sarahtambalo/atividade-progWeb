# **Atividade pw01**

## **1. Descreva as motivações para o desenvolvimento de aplicações baseadas em internet?**
- **Acessibilidade Ubíqua**
    - Disponibilidade 24/7: Usuários podem acessar de qualquer lugar, a qualquer hora;
    - Multiplataforma: Funcionam em diferentes dispositivos (computadores, tablets, smartphones) sem necessidade de versões específicas;
    - Sem instalação: Elimina a necessidade de download e instalação de software.

- **Custos Reduzidos**
    - Trabalho simultâneo: Múltiplos usuários podem interagir com os mesmos dados;
    - Compartilhamento instantâneo: Facilidade para compartilhar informações e recursos;
    - Sincronização automática: Dados sempre atualizados para todos os usuários.

- **Modelo de Negócios Atraente**
    - Assinaturas SaaS: Receita recorrente através de modelos de assinatura;
    - Freemium: Oferecer versões básicas gratuitas e recursos premium pagos;
    - Alcance global: Potencial para atingir mercados internacionais.

- **Atualizações Contínuas**
    - Deployment contínuo: Correções e novas funcionalidades entregues rapidamente;
    - Feedback imediato: Possibilidade de coletar e implementar sugestões dos usuários;
    - A/B testing: Fácil experimentação de novas funcionalidades.

- **Integração e Ecossistema**
    - APIs: Facilidade para integrar com outros serviços e plataformas;
    - Mashups: Combinar dados e funcionalidades de diferentes fontes;
    - Ecosystemas digitais: Participar de plataformas maiores (marketplaces, redes sociais).

- **Dados e Analytics**
    - Coleta de dados: Capacidade de reunir informações sobre comportamento do usuário;
    - Personalização: Adaptar experiência baseada em dados coletados;
    - Business intelligence: Tomar decisões baseadas em métricas reais de uso.

- **Escalabilidade**
    - Elasticidade: Capacidade de crescer conforme demanda;
    - Distribuição geográfica: Usar CDNs e múltiplas regiões para melhor performance;
    - Alta disponibilidade: Arquiteturas redundantes garantem uptime.

- **Segurança Centralizada**
    - Proteção de dados: Medidas de segurança implementadas no servidor;
    - Backup automatizado: Facilidade para implementar políticas de backup;
    - Conformidade: Centralização facilita adequação a regulamentações (LGPD, GDPR).

- **Inovação Tecnológica**
    - Novas tecnologias web: Aproveitar avanços em HTML5, WebAssembly, etc.;
    - Inteligência artificial: Integração com serviços de IA em nuvem;
    - IoT: Conectar e gerenciar dispositivos através da internet.

- **Sustentabilidade**
    - Menor consumo de energia: Dispositivos locais exigem menos processamento;
    - Otimização de recursos: Compartilhamento eficiente de infraestrutura;
    - Redução de e-waste: Hardware local menos exigente dura mais tempo.

- **Vantagens Competitivas**
    - Time-to-market reduzido: Desenvolvimento e deploy mais rápidos;
    - Agilidade nos negócios: Capacidade de pivotar rapidamente;
    - Experiência consistente: Interface uniforme para todos os usuários.


## **2. Quais as funções de um servidor de aplicação?**
Um servidor de aplicação é uma plataforma que fornece o ambiente e os serviços necessários para executar aplicações, especialmente aplicações web e corporativas. Suas principais funções incluem:

**1. Gerenciamento do Ciclo de Vida da Aplicação**
- Deployment: Disponibiliza mecanismos para implantar, atualizar e remover aplicações;
- Inicialização e encerramento: Controla o start/stop de componentes da aplicação;
- Isolamento: Executa múltiplas aplicações em ambientes segregados.

**2. Gerenciamento de Conexões**
- Pool de conexões: Mantém um cache de conexões com bancos de dados para reutilização;
- Gerenciamento de threads: Controla threads para processamento simultâneo de requisições;
- Balanceamento de carga: Distribui requisições entre múltiplas instâncias.

**3. Segurança**
- Autenticação: Verifica identidade de usuários e sistemas;
- Autorização: Controla acesso a recursos baseado em papéis e permissões;
- Criptografia: Gerencia certificados SSL/TLS para comunicação segura;
- Proteção contra ataques: Implementa medidas contra ameaças comuns.

**4. Gerenciamento de Transações**
- Transações distribuídas: Coordena transações que envolvem múltiplos recursos;
- Atomicidade: Garante que operações sejam completadas ou revertidas completamente;
- Isolamento: Gerencia concorrência entre transações simultâneas.

**5. Persistência e Acesso a Dados**
- ORM (Object-Relational Mapping): Fornece abstração para acesso a bancos de dados;
- Caching: Mantém dados em memória para acesso rápido;
- Data sources: Gerencia conexões com diferentes fontes de dados.

**6. Mensageria e Comunicação**
- Filas de mensagens: Gerencia comunicação assíncrona entre componentes;
- Publicação/assinatura: Implementa padrões de comunicação baseados em eventos;
- WebServices: Fornece suporte para SOAP, REST e outros protocolos.

**7. Gerenciamento de Estado**
- Sessões HTTP: Mantém estado de usuários entre requisições;
- Estado de componentes: Gerencia ciclo de vida de objetos de negócio;
- Clustering: Compartilha estado entre múltiplos servidores.

**8. Log e Monitoramento**
- Logging: Registra eventos, erros e atividades da aplicação;
- Métricas: Coleta dados de performance e utilização;
- Auditoria: Mantém trilhas de ações importantes para compliance.

**9. Integração com Sistemas Externos**
- Conectores: Fornece adaptadores para ERPs, CRMs e outros sistemas legados;
- Adaptadores de protocolo: Suporta diversos protocolos de comunicação;
- Transformação de dados: Converte formatos entre sistemas diferentes.

**10. Alta Disponibilidade e Escalabilidade**
- Failover: Redireciona requisições automaticamente em caso de falha;
- Replicação: Mantém cópias sincronizadas para redundância;
- Escalonamento automático: Ajusta recursos conforme demanda.

**11. Gerenciamento de Recursos**
- Thread pooling: Otimiza uso de threads para processamento concorrente;
- Memory management: Controla alocação e liberação de memória;
- Resource adapters: Gerencia acesso a recursos externos.

**12. Suporte a Containers e Virtualização**
- Isolamento de aplicações: Executa múltiplas aplicações em containers separados;
- Orquestração: Coordena implantação em ambientes containerizados;
- Microserviços: Suporta arquiteturas baseadas em serviços distribuídos.

**13. Serviços de Namespace e Diretório**
- JNDI (Java Naming and Directory Interface): Fornece serviço de nomes para localizar recursos;
- Binding dinâmico: Permite descoberta de serviços em tempo de execução.

**14. Serviços Web e APIs**
- Endpoints REST/SOAP: Disponibiliza interfaces para consumo por clientes;
- Documentação automática: Gera documentação de APIs;
- Versionamento: Gerencia diferentes versões de APIs simultaneamente.

**Exemplos de Servidores de Aplicação Populares:**
- Apache Tomcat (leve, focado em Java Servlets)
- JBoss/WildFly (completo, Java EE)
- WebSphere (IBM, enterprise)
- WebLogic (Oracle, enterprise)
- Node.js (JavaScript, não tradicional mas funciona como servidor de aplicação)
- IIS (Microsoft, .NET)
- Gunicorn (Python)
- Puma/Unicorn (Ruby)

Estas funções tornam o servidor de aplicação uma peça fundamental na arquitetura de sistemas corporativos, abstraindo complexidades e permitindo que os desenvolvedores foquem na lógica de negócio da aplicação.


## **3. Quais as diferenças de uma página dinâmica e uma página estática?**

### **Página Estática**

Uma página estática é entregue ao navegador exatamente como está armazenada no servidor, sem processamento adicional.

- **Características principais:**
    - Conteúdo fixo: O mesmo conteúdo é exibido para todos os usuários
    - Arquivos pré-definidos: Geralmente arquivos .html, .css, .js
    - Sem processamento no servidor: O servidor apenas localiza e envia o arquivo
    - Entrega rápida: Mínimo processamento requerido
    - Armazenamento simples: Arquivos individuais no sistema de arquivos

    **Exemplo de código (HTML estático):**
    ```
    <!DOCTYPE html>
    <html>
    <head>
        <title>Meu Site</title>
    </head>
    <body>
        <h1>Bem-vindo ao meu site</h1>
        <p>Este conteúdo é sempre o mesmo para todos.</p>
        <p>Última atualização: 01/01/2024</p>
    </body>
    </html>
    ```

    **Exemplos de Páginas Estáticas:**
    - Landing pages institucionais simples
    - Documentação técnica
    - Portfólios pessoais
    - Blogs com poucas atualizações
    - Páginas de "Sobre nós" ou "Contato"

    **Tecnologias Comuns Para Páginas Estáticas:**
    - HTML, CSS, JavaScript puro
    - Geradores de sites estáticos (Jekyll, Hugo, Gatsby)
    - CDNs (Cloudflare, Netlify, Vercel)
    - GitHub Pages

    **Exemplo de Fluxo Estático:**
    ```
    1. Usuário → Requisição → Servidor
    2. Servidor → Localiza arquivo → Disco
    3. Servidor → Envia arquivo → Usuário
    4. Navegador → Renderiza página
    ```


### **Página Dinâmica**

Uma página dinâmica é gerada "em tempo real" pelo servidor, combinando templates com dados variáveis.

- **Características principais:**
    - Conteúdo personalizado: Pode variar por usuário, contexto ou dados
    - Processamento server-side: O servidor executa código para gerar o HTML
    - Integração com banco de dados: Busca informações atualizadas
    - Interatividade avançada: Responde a ações do usuário
    - Geração sob demanda: Criada no momento da requisição

    **Exemplo de código (PHP dinâmico):**
    ```
    <!DOCTYPE html>
    <html>
    <head>
        <title>Perfil do Usuário</title>
    </head>
    <body>
        <h1>Bem-vindo, <?php echo $usuario_nome; ?>!</h1>
        <p>Seu saldo atual é: R$ <?php echo $saldo; ?></p>
        <p>Último acesso: <?php echo $ultimo_login; ?></p>
        
        <?php if($saldo < 0): ?>
            <p style="color: red">Atenção: saldo negativo!</p>
        <?php endif; ?>
    </body>
    </html>
    ```

    **Exemplos de Páginas Dinâmicas:**
    - Redes sociais (Facebook, Instagram)
    - E-commerces (Amazon, Mercado Livre)
    - Portais de notícias
    - Internet Banking
    - Sistemas de gestão (ERP, CRM)
    - Fóruns e comunidades online

    **Tecnologias Comuns Para Páginas Dinâmicas:**
    - Back-end: PHP, Python (Django/Flask), Ruby (Rails), Java (Spring), Node.js
    - Bancos de dados: MySQL, PostgreSQL, MongoDB
    - Templates: Twig, Blade, EJS, JSP
    - Frameworks front-end: React, Vue, Angular (com integração back-end)

    **Exemplo de Fluxo Dinâmico:**
    ```
    1. Usuário → Requisição → Servidor
    2. Servidor → Executa código → Lógica de negócio
    3. Código → Consulta dados → Banco de Dados
    4. Banco → Retorna dados → Código
    5. Código → Gera HTML → Template
    6. Servidor → Envia HTML → Usuário
    7. Navegador → Renderiza página
    ```

### **Casos de Uso Híbridos**

Muitos sites modernos combinam ambas abordagens:
- Jamstack: Páginas estáticas com conteúdo dinâmico via JavaScript
- SSG (Static Site Generation): Gera páginas estáticas a partir de dados dinâmicos
- ISR (Incremental Static Regeneration): Atualiza páginas estáticas periodicamente
- Hydration: Páginas estáticas que se tornam interativas no cliente

### **Escolhendo a Abordagem**

Use páginas estáticas quando:
- O conteúdo raramente muda
- A performance é crítica
- Orçamento é limitado
- Segurança simples é suficiente
- Poucas páginas são necessárias

Use páginas dinâmicas quando:
- Conteúdo muda frequentemente
- Precisa de personalização por usuário
- Há interação com banco de dados
- Funcionalidades complexas são necessárias
- Muitas páginas com estrutura similar

> A escolha entre estático e dinâmico depende das necessidades específicas do projeto, considerando fatores como frequência de atualizações, necessidade de personalização, orçamento e requisitos de performance.