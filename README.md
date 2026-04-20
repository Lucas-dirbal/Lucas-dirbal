<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lucas | Perfil GitHub</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: linear-gradient(135deg, #0f172a, #1e293b, #334155);
      color: #f8fafc;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 30px;
    }

    .card {
      max-width: 900px;
      width: 100%;
      background: rgba(15, 23, 42, 0.9);
      border: 1px solid rgba(255, 255, 255, 0.08);
      border-radius: 24px;
      padding: 40px;
      box-shadow: 0 20px 50px rgba(0, 0, 0, 0.35);
      backdrop-filter: blur(10px);
    }

    .title {
      font-size: 2.5rem;
      color: #38bdf8;
      margin-bottom: 10px;
    }

    .subtitle {
      font-size: 1.1rem;
      color: #cbd5e1;
      margin-bottom: 30px;
      line-height: 1.6;
    }

    .section {
      margin-bottom: 28px;
    }

    .section h2 {
      color: #facc15;
      margin-bottom: 10px;
      font-size: 1.3rem;
    }

    .section p,
    .section li {
      color: #e2e8f0;
      line-height: 1.7;
      font-size: 1rem;
    }

    ul {
      padding-left: 20px;
    }

    .badges {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 10px;
    }

    .badge {
      background: #1e40af;
      color: #fff;
      padding: 10px 16px;
      border-radius: 999px;
      font-size: 0.95rem;
      font-weight: bold;
      box-shadow: 0 8px 20px rgba(30, 64, 175, 0.3);
    }

    .highlight {
      color: #38bdf8;
      font-weight: bold;
    }

    .footer {
      margin-top: 30px;
      text-align: center;
      color: #94a3b8;
      font-size: 0.95rem;
      border-top: 1px solid rgba(255,255,255,0.08);
      padding-top: 20px;
    }

    @media (max-width: 768px) {
      .card {
        padding: 25px;
      }

      .title {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1 class="title">👋 Olá, eu sou o Lucas</h1>
    <p class="subtitle">
      Trabalho com <span class="highlight">suporte e desenvolvimento</span>, atuando com
      <span class="highlight">banco de dados</span>, <span class="highlight">regras fiscais</span> e
      <span class="highlight">melhorias em sistemas ERP</span>. Gosto de transformar problemas do dia a dia
      em soluções práticas e funcionais.
    </p>

    <div class="section">
      <h2>🚀 Tecnologias e Ferramentas</h2>
      <div class="badges">
        <span class="badge">HTML</span>
        <span class="badge">CSS</span>
        <span class="badge">SQL</span>
        <span class="badge">Firebird 2.5</span>
        <span class="badge">IBExpert</span>
      </div>
    </div>

    <div class="section">
      <h2>🛠️ O que eu faço no dia a dia</h2>
      <ul>
        <li>Análise e correção de dados em banco de dados</li>
        <li>Criação de queries, updates e validações em SQL</li>
        <li>Suporte técnico e atendimento a clientes</li>
        <li>Melhorias e ajustes em sistemas ERP</li>
        <li>Identificação de inconsistências como duplicidades e problemas fiscais</li>
        <li>Apoio em processos como CFOP, NFS-e, CIOT e outras rotinas do sistema</li>
      </ul>
    </div>

    <div class="section">
      <h2>💡 Interesses</h2>
      <p>
        Tenho interesse em <span class="highlight">automação de processos</span>,
        desenvolvimento web e criação de soluções que facilitem a rotina dos usuários.
        Também gosto de aprender na prática, criando ideias que ajudam a fixar melhor o uso das tecnologias.
      </p>
    </div>

    <div class="section">
      <h2>📚 Fora do código</h2>
      <p>
        Quando não estou trabalhando ou estudando, gosto de jogar <span class="highlight">vôlei</span>
        e aproveitar o tempo com amigos e família.
      </p>
    </div>

    <div class="section">
      <h2>✨ Objetivo</h2>
      <p>
        Evoluir cada vez mais como desenvolvedor, aprofundando meus conhecimentos em banco de dados,
        suporte técnico e desenvolvimento web, sempre buscando criar soluções úteis e eficientes.
      </p>
    </div>

    <div class="footer">
      Feito com dedicação por Lucas 💙
    </div>
  </div>
</body>
</html>
