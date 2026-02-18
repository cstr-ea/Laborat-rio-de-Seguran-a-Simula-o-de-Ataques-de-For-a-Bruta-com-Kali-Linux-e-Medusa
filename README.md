# Laborat-rio-de-Seguran-a-Simula-o-de-Ataques-de-For-a-Bruta-com-Kali-Linux-e-Medusa

🧬 Mapeamento MITRE ATT&CK

Os cenários simulados se enquadram nas seguintes técnicas do framework MITRE:

Técnica	ID	Descrição
Brute Force	T1110	Tentativas repetidas de autenticação
Password Spraying	T1110.003	Teste de senha comum contra múltiplos usuários
Valid Accounts	T1078	Uso de credenciais legítimas comprometidas
🎯 Fase da Kill Chain

Reconhecimento

Credencial Access

Initial Access

Isso mostra que você entende ataque em nível estratégico, não só ferramenta.

📊 Análise de Risco (Visão ISO 27005)

Já que você está estudando gestão de risco, vamos integrar isso.

Ativo Avaliado

Servidor Linux vulnerável (Metasploitable)

Ameaça

Ataque de força bruta

Vulnerabilidade

Senhas fracas

Ausência de bloqueio de conta

Falta de MFA

Impacto

Acesso não autorizado

Vazamento de dados

Escalada de privilégio

Probabilidade

Alta (devido à ausência de controles)

Nível de Risco

🔴 Alto

Isso mostra maturidade técnica + visão de governança.

🛡️ Perspectiva Blue Team (Detecção e Resposta)

Agora você não é só ofensivo — você é analista.

🔍 Indicadores de Ataque (IOCs)

Múltiplas tentativas de login em curto período

Vários usuários testados com mesma senha

Acessos fora do horário comercial

IP interno gerando alto volume de autenticações

📈 Estratégias de Detecção

Monitoramento de logs de autenticação

Alertas para tentativas consecutivas falhas

Correlação de eventos

Monitoramento via SIEM

🚨 Resposta ao Incidente

Bloqueio temporário da conta

Reset forçado de senha

Investigação de logs

Análise de origem

Atualização de políticas de senha

🧠 Threat Modeling Simplificado
Atacante:

Usuário interno malicioso ou atacante com acesso à rede interna

Superfície de Ataque:

FTP

SMB

Aplicação Web

Vetor:

Autenticação fraca

Resultado:

Comprometimento total do sistema

📚 Evolução Técnica do Projeto

Adicione esta seção:

🔬 Evolução do Laboratório
Versão	Evolução
v1	Brute force básico
v2	Inclusão de password spraying
v3	Mapeamento MITRE
v4	Análise de risco
v5	Estratégias de detecção

Isso demonstra pensamento incremental e maturidade.

💼 Como Recrutador Vai Ver Você Agora

Antes:

Fez um laboratório de brute force.

Agora:

Entende MITRE ATT&CK
Entende gestão de risco
Entende detecção
Entende resposta
Conecta ofensiva e defensiva

Isso te coloca acima de 80% dos iniciantes.

🧩 Quer Subir MAIS Ainda?

Podemos adicionar:

📊 Matriz de risco visual

📈 Simulação de relatório executivo

🧾 Modelo de relatório técnico estilo empresa

🕵️ Simulação de incidente SOC (timeline)

🧠 Análise comportamental de ataque
