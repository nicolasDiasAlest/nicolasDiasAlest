<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>READMEs Incríveis do GitHub</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            color: white;
            padding: 40px 0;
            margin-bottom: 40px;
        }
        
        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        
        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .card {
            background: white;
            border-radius: 12px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0,0,0,0.2);
        }
        
        .card h2 {
            color: #667eea;
            margin-bottom: 10px;
            font-size: 1.8rem;
        }
        
        .card h3 {
            color: #764ba2;
            margin: 20px 0 10px 0;
            font-size: 1.3rem;
        }
        
        .card p {
            color: #666;
            margin-bottom: 15px;
        }
        
        .badge {
            display: inline-block;
            background: #667eea;
            color: white;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            margin-right: 8px;
            margin-bottom: 8px;
        }
        
        .link-btn {
            display: inline-block;
            background: #667eea;
            color: white;
            padding: 10px 20px;
            border-radius: 6px;
            text-decoration: none;
            margin-top: 10px;
            transition: background 0.3s;
        }
        
        .link-btn:hover {
            background: #764ba2;
        }
        
        .stats {
            display: flex;
            gap: 20px;
            margin: 15px 0;
            flex-wrap: wrap;
        }
        
        .stat-item {
            background: #f7f7f7;
            padding: 10px 15px;
            border-radius: 6px;
        }
        
        .stat-item strong {
            color: #667eea;
        }
        
        .tools-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .tool-card {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid #667eea;
        }
        
        .tool-card h4 {
            color: #333;
            margin-bottom: 8px;
        }
        
        ul {
            margin-left: 20px;
            margin-top: 10px;
        }
        
        li {
            margin-bottom: 8px;
        }
        
        code {
            background: #f4f4f4;
            padding: 2px 6px;
            border-radius: 3px;
            font-family: 'Courier New', monospace;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🚀 READMEs Incríveis do GitHub</h1>
            <p>Uma coleção curada dos melhores READMEs encontrados na web</p>
        </header>

        <div class="card">
            <h2>📊 Por que READMEs importam?</h2>
            <div class="stats">
                <div class="stat-item">
                    <strong>93%</strong> mais estrelas ⭐
                </div>
                <div class="stat-item">
                    <strong>416%</strong> mais forks 🍴
                </div>
                <div class="stat-item">
                    <strong>193%</strong> mais pull requests 🔄
                </div>
            </div>
            <p>Repositórios com READMEs de alta qualidade têm desempenho significativamente melhor!</p>
        </div>

        <div class="card">
            <h2>🌟 Melhores Exemplos de READMEs</h2>
            
            <h3>ai/size-limit</h3>
            <p>Logo do projeto, descrição clara, screenshot, instruções passo-a-passo de instalação.</p>
            <span class="badge">Logo</span>
            <span class="badge">Screenshots</span>
            <span class="badge">Instalação Clara</span>
            <a href="https://github.com/ai/size-limit" class="link-btn" target="_blank">Ver Repositório</a>
            
            <h3>alichtman/shallow-backup</h3>
            <p>Descrição clara do projeto, GIF demo, TOC para navegação fácil, badges, links para leitura adicional.</p>
            <span class="badge">GIF Demo</span>
            <span class="badge">TOC</span>
            <span class="badge">Badges</span>
            <a href="https://github.com/alichtman/shallow-backup" class="link-btn" target="_blank">Ver Repositório</a>
            
            <h3>alichtman/stronghold</h3>
            <p>Logo do projeto, descrição clara, GIF demo, TOC, badges, instruções simples de instalação.</p>
            <span class="badge">Logo</span>
            <span class="badge">GIF Demo</span>
            <span class="badge">Simples</span>
            <a href="https://github.com/alichtman/stronghold" class="link-btn" target="_blank">Ver Repositório</a>
            
            <h3>amitmerchant1990/electron-markdownify</h3>
            <p>Logo do projeto, descrição minimalista, GIF demo, recursos principais, guia de instalação, créditos.</p>
            <span class="badge">Minimalista</span>
            <span class="badge">GIF Demo</span>
            <span class="badge">Recursos</span>
            <a href="https://github.com/amitmerchant1990/electron-markdownify" class="link-btn" target="_blank">Ver Repositório</a>
            
            <h3>amplication/amplication</h3>
            <p>Logo claro do projeto, explicação breve, demos visuais, setup rápido.</p>
            <span class="badge">Logo Claro</span>
            <span class="badge">Setup Rápido</span>
            <a href="https://github.com/amplication/amplication" class="link-btn" target="_blank">Ver Repositório</a>
        </div>

        <div class="card">
            <h2>🛠️ Ferramentas para Criar READMEs</h2>
            
            <div class="tools-grid">
                <div class="tool-card">
                    <h4>🎨 Shields.io</h4>
                    <p>API completa para criar badges customizadas</p>
                    <a href="https://shields.io" target="_blank">shields.io</a>
                </div>
                
                <div class="tool-card">
                    <h4>🏷️ Badges 4 README</h4>
                    <p>Mais de 700 badges em 35+ categorias</p>
                    <a href="https://github.com/alexandresanlim/Badges4-README.md-Profile" target="_blank">Ver GitHub</a>
                </div>
                
                <div class="tool-card">
                    <h4>✨ Forthebadge</h4>
                    <p>Badges pré-definidas prontas para usar</p>
                    <a href="https://forthebadge.com" target="_blank">forthebadge.com</a>
                </div>
                
                <div class="tool-card">
                    <h4>🖼️ Carbon</h4>
                    <p>Screenshots bonitos de código</p>
                    <a href="https://carbon.now.sh" target="_blank">carbon.now.sh</a>
                </div>
                
                <div class="tool-card">
                    <h4>📝 readme.so</h4>
                    <p>Editor visual de README</p>
                    <a href="https://readme.so" target="_blank">readme.so</a>
                </div>
                
                <div class="tool-card">
                    <h4>🤖 AI README Generator</h4>
                    <p>Gera README do seu código automaticamente</p>
                    <a href="https://readmecodegen.vercel.app" target="_blank">Ver Gerador</a>
                </div>
            </div>
        </div>

        <div class="card">
            <h2>📚 Recursos Adicionais</h2>
            
            <h3>Listas Curadas</h3>
            <ul>
                <li><strong>Awesome README:</strong> Lista curada de READMEs incríveis com exemplos de elementos visuais, imagens, GIFs e formatação</li>
                <li><strong>Cool GitHub Profile READMEs:</strong> Coleção de perfis criativos e visuais do GitHub</li>
                <li><strong>A Good README Template:</strong> Template completo para começar</li>
            </ul>
            
            <h3>Guias e Tutoriais</h3>
            <ul>
                <li><strong>How to Write an Awesome README:</strong> Guia completo da Bomberbot com análise de 1.5M de repositórios</li>
                <li><strong>From Meh to Marvelous:</strong> Guia definitivo para criar perfis matadores no GitHub</li>
                <li><strong>Best Practices for GitHub README:</strong> Práticas recomendadas com formatação e elementos visuais</li>
            </ul>
            
            <h3>Elementos Essenciais</h3>
            <ul>
                <li>✅ Título descritivo e conciso</li>
                <li>✅ Logo ou banner visual</li>
                <li>✅ Badges (build, license, version)</li>
                <li>✅ Screenshots ou GIFs de demo</li>
                <li>✅ Índice (TOC) para READMEs longos</li>
                <li>✅ Instruções de instalação claras</li>
                <li>✅ Exemplos de uso</li>
                <li>✅ Tecnologias utilizadas</li>
                <li>✅ Guia de contribuição</li>
                <li>✅ Licença do projeto</li>
            </ul>
        </div>

        <div class="card">
            <h2>💡 Dicas Rápidas</h2>
            <ul>
                <li><strong>Regra dos 30 segundos:</strong> Visitantes devem entender seu projeto em 30 segundos</li>
                <li><strong>Foque no problema:</strong> Explique qual problema você resolve antes de explicar o código</li>
                <li><strong>Use visuais:</strong> GIFs valem mais que mil palavras</li>
                <li><strong>Syntax highlighting:</strong> Sempre especifique a linguagem nos blocos de código</li>
                <li><strong>Mantenha atualizado:</strong> README desatualizado é pior que nenhum README</li>
            </ul>
        </div>

        <div class="card" style="text-align: center; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white;">
            <h2 style="color: white;">🚀 Agora é com você!</h2>
            <p>Use esses exemplos e ferramentas para criar READMEs incríveis</p>
            <p style="margin-top: 20px; font-size: 0.9rem; opacity: 0.8;">Compilado por Nicolas Dias - Alest Consultoria</p>
        </div>
    </div>
</body>
</html>
