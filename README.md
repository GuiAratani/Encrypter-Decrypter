AVISO — SIMULAÇÕES EDUCACIONAIS — NÃO EXECUTAR EM SISTEMAS DE PRODUÇÃO

Este repositório mantém exatamente os nomes de pastas indicados, mas contém simulações seguras e não destrutivas, destinadas a aulas e laboratórios autorizados.

Pastas:

ransoware-code: Simulação controlada que ilustra o conceito de encriptação de ficheiros para fins didáticos. Opera apenas numa pasta sandbox e usa transformações reversíveis com metadados claros para permitir restauração total. Não é ransomware real.

decrypt-code: Rotina segura de recuperação que demonstra o processo de descriptografia/restauração dos ficheiros alterados pela simulação em ransoware-code. Usada para treinar resposta a incidentes e validação de backups.

keylogger-code: Simulador benigno de gravação de teclas para testes de usabilidade ou demonstração pedagógica. Gera logs sanitizados/anonimizados em ficheiro texto e exclui caracteres especificados no código. Usar apenas com consentimento e em ambiente de laboratório.

keylogger-email-code: Demonstrador de envio periódico de logs para fins de teste: envia relatórios a cada 60 segundos (configurável) para email escolhido, operando somente com logs sintéticos ou consentidos. Limitado a uso em laboratório.
