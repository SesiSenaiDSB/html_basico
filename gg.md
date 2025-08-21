Ilustração Semântica do Código HTML
Abaixo está uma representação visual das partes do código HTML fornecido, organizada em retângulos que representam a estrutura semântica do documento. Cada seção principal é descrita com sua função e os elementos que a compõem.
graph TD
    A[Documento HTML<br><code>&lt;!DOCTYPE html&gt;</code>] --> B[html<br><code>&lt;html lang='pt-br'&gt;</code>]
    B --> C[head<br><code>&lt;head&gt;</code>]
    B --> D[body<br><code>&lt;body&gt;</code>]

    C --> C1[meta charset<br><code>&lt;meta charset='UTF-8'&gt;</code>]
    C --> C2[meta viewport<br><code>&lt;meta name='viewport' ...&gt;</code>]
    C --> C3[title<br><code>&lt;title&gt;Portifólio - Demonstração HTML Completo&lt;/title&gt;</code>]

    D --> E[header<br><code>&lt;header&gt;</code>]
    D --> F[main<br><code>&lt;main&gt;</code>]
    D --> G[footer<br><code>&lt;footer&gt;</code>]

    E --> E1[h1<br><code>&lt;h1&gt;João Silva - Desenvolvedor Web&lt;/h1&gt;</code>]
    E --> E2[nav<br><code>&lt;nav&gt;</code>]
    E2 --> E2a[ul<br><code>&lt;ul&gt;</code>]
    E2a --> E2a1[li - Sobre<br><code>&lt;li&gt;&lt;a href='#sobre'&gt;Sobre&lt;/a&gt;&lt;/li&gt;</code>]
    E2a --> E2a2[li - Projetos<br><code>&lt;li&gt;&lt;a href='#projetos'&gt;Projetos&lt;/a&gt;&lt;/li&gt;</code>]
    E2a --> E2a3[li - Contato<br><code>&lt;li&gt;&lt;a href='#contato'&gt;Contato&lt;/a&gt;&lt;/li&gt;</code>]

    F --> F1[section - Sobre<br><code>&lt;section id='sobre'&gt;</code>]
    F --> F2[section - Projetos<br><code>&lt;section id='projetos'&gt;</code>]
    F --> F3[section - Contato<br><code>&lt;section id='contato'&gt;</code>]

    F1 --> F1a[h2<br><code>&lt;h2&gt;Sobre mim&lt;/h2&gt;</code>]
    F1 --> F1b[img<br><code>&lt;img src='assets/avatar_m.jpg' ...&gt;</code>]
    F1 --> F1c[p<br><code>&lt;p&gt;Ssou estudante...&lt;/p&gt;</code>]
    F1 --> F1d[p<br><code>&lt;p&gt;Tenho conhecimento...&lt;/p&gt;</code>]
    F1 --> F1e[h3<br><code>&lt;h3&gt;Minhas habilidades&lt;/h3&gt;</code>]
    F1 --> F1f[ul<br><code>&lt;ul&gt;</code>]
    F1f --> F1f1[li - HTML5<br><code>&lt;li&gt;HTML5 Semântico&lt;/li&gt;</code>]
    F1f --> F1f2[li - CSS3<br><code>&lt;li&gt;CSS3 e Responsividade&lt;/li&gt;</code>]
    F1f --> F1f3[li - Formulários<br><code>&lt;li&gt;Formulários e Validação&lt;/li&gt;</code>]
    F1f --> F1f4[li - Estruturação<br><code>&lt;li&gt;Estruturação de dados&lt;/li&gt;</code>]

    F2 --> F2a[h2<br><code>&lt;h2&gt;Meus projetos&lt;/h2&gt;</code>]
    F2 --> F2b[table<br><code>&lt;table border='1' ...&gt;</code>]
    F2b --> F2b1[thead<br><code>&lt;thead&gt;</code>]
    F2b --> F2b2[tbody<br><code>&lt;tbody&gt;</code>]
    F2b1 --> F2b1a[tr<br><code>&lt;tr&gt;</code>]
    F2b1a --> F2b1a1[th - Projeto<br><code>&lt;th&gt;Projeto&lt;/th&gt;</code>]
    F2b1a --> F2b1a2[th - Tecnologias<br><code>&lt;th&gt;Tecnologias&lt;/th&gt;</code>]
    F2b1a --> F2b1a3[th - Status<br><code>&lt;th&gt;Status&lt;/th&gt;</code>]
    F2b1a --> F2b1a4[th - Link<br><code>&lt;th&gt;Link&lt;/th&gt;</code>]
    F2b2 --> F2b2a[tr - Site pessoal<br><code>&lt;tr&gt;</code>]
    F2b2 --> F2b2b[tr - Sistema de cadastro<br><code>&lt;tr&gt;</code>]
    F2b2a --> F2b2a1[td<br><code>&lt;td&gt;Site pessoal&lt;/td&gt;</code>]
    F2b2a --> F2b2a2[td<br><code>&lt;td&gt;HTML, CSS&lt;/td&gt;</code>]
    F2b2a --> F2b2a3[td<br><code>&lt;td&gt;Concluído&lt;/td&gt;</code>]
    F2b2a --> F2b2a4[td<br><code>&lt;td&gt;&lt;a href='projeto1.html'&gt;...&lt;/a&gt;&lt;/td&gt;</code>]
    F2b2b --> F2b2b1[td<br><code>&lt;td&gt;Sistema de cadastro&lt;/td&gt;</code>]
    F2b2b --> F2b2b2[td<br><code>&lt;td&gt;HTML, CSS e Java Script&lt;/td&gt;</code>]
    F2b2b --> F2b2b3[td<br><code>&lt;td&gt;Em andamento&lt;/td&gt;</code>]
    F2b2b --> F2b2b4[td<br><code>&lt;td&gt;&lt;a href='projeto2.html'&gt;...&lt;/a&gt;&lt;/td&gt;</code>]

    F3 --> F3a[h2<br><code>&lt;h2&gt;Entre em contato&lt;/h2&gt;</code>]
    F3 --> F3b[form<br><code>&lt;form action='enviar.php'&gt;</code>]
    F3b --> F3b1[fieldset<br><code>&lt;fieldset&gt;</code>]
    F3b1 --> F3b1a[legend<br><code>&lt;legend&gt;Dados do contato&lt;/legend&gt;</code>]
    F3b1 --> F3b1b[label - Nome<br><code>&lt;label for='nome'&gt;Nome&lt;/label&gt;</code>]
    F3b1 --> F3b1c[input - Nome<br><code>&lt;input type='text' id='nome' ...&gt;</code>]
    F3b1 --> F3b1d[label - Email<br><code>&lt;label for='email'&gt;Email&lt;/label&gt;</code>]
    F3b1 --> F3b1e[input - Email<br><code>&lt;input type='email' id='email' ...&gt;</code>]
    F3b1 --> F3b1f[label - Assunto<br><code>&lt;label for='assunto'&gt;Assunto:&lt;/label&gt;</code>]
    F3b1 --> F3b1g[select<br><code>&lt;select name='assunto' id='assunto'&gt;</code>]
    F3b1g --> F3b1g1[option - Trabalho<br><code>&lt;option value='trabalho'&gt;...&lt;/option&gt;</code>]
    F3b1g --> F3b1g2[option - Projeto<br><code>&lt;option value='projeto'&gt;...&lt;/option&gt;</code>]
    F3b1g --> F3b1g3[option - Geral<br><code>&lt;option value='geral'&gt;...&lt;/option&gt;</code>]
    F3b1 --> F3b1h[label - Mensagem<br><code>&lt;label for='mensagem'&gt;Mensagem:&lt;/label&gt;</code>]
    F3b1 --> F3b1i[textarea<br><code>&lt;textarea name='mensagem' id='mensagem' ...&gt;</code>]
    F3b1 --> F3b1j[input - Submit<br><code>&lt;input type='submit' value='Enviar mensagem'&gt;</code>]

    G --> G1[p - Copyright<br><code>&lt;p&gt;&copy; 2025 João Silva...&lt;/p&gt;</code>]
    G --> G2[p - Contatos<br><code>&lt;p&gt;</code>]
    G2 --> G2a[a - Email<br><code>&lt;a href='mailto:joao@exemplo.com'&gt;...&lt;/a&gt;</code>]
    G2 --> G2b[a - Telefone<br><code>&lt;a href='tel:5511999998888'&gt;...&lt;/a&gt;</code>]

Descrição da Ilustração

Documento HTML: Raiz do documento, definida pelo <!DOCTYPE html> e <html lang="pt-br">.
Head: Contém metadados como codificação (meta charset), configuração de viewport e título da página.
Body: Contém o conteúdo visível, dividido em:
Header: Inclui o título principal (h1) e a navegação (nav) com links.
Main: Contém três seções semânticas:
Sobre: Apresenta informações pessoais, uma imagem e uma lista de habilidades.
Projetos: Exibe uma tabela com informações sobre projetos.
Contato: Contém um formulário para contato com campos de entrada.


Footer: Inclui informações de copyright e links de contato (email e telefone).



A ilustração usa a sintaxe Mermaid para criar um diagrama de fluxo que representa a hierarquia semântica do código HTML.