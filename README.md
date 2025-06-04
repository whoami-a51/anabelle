🚫 Aviso Legal

Este material é disponibilizado exclusivamente para fins educacionais e de pesquisa em segurança cibernética. O uso indevido pode configurar crime previsto em lei.
``` NÃO FAÇA O DOWNLOAD E EXECUTE EM SEU COMPUTADOR PESSOAL. ```  

🛡️ Ransomware Anabelle – Análise Resumida

Anabelle é um ransomware criado com fins maliciosos, mas com forte caráter de prova de conceito (PoC). Ele ficou conhecido por combinar técnicas de criptografia, controle de dispositivos e sabotagem de sistemas Windows.  

![descrição](/anabelle.jpg)  

🔍 Principais Características
- Linguagem: Desenvolvido em C#
- Criptografia: Usa o algoritmo AES para cifrar arquivos do sistema.
- Propagação: Tenta se espalhar por dispositivos USB automaticamente.
- Serviços: Finaliza processos críticos como o Gerenciador de Tarefas, CMD, Regedit, etc.

  Sabotagem:
   -   Desativa o Firewall e Windows Defender
   -   Reinstala softwares de segurança

  Controle Remoto: Se conecta a um servidor C2 (Command & Control) para receber comandos.
 
  Modificações no sistema:
   - Altera o papel de parede
   - Desativa funcionalidades do Windows
 
  Curiosidade: Contém uma mensagem dizendo que o objetivo é mostrar como os antivírus são ineficientes.

⚠️ Observação

O Anabelle não foi feito para fins financeiros, mas sim como crítica à (in)eficiência das soluções de segurança. Apesar disso, é um malware completo e perigoso, capaz de causar sérios danos.
