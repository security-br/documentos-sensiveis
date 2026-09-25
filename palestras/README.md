| # | Data | Local | Slides | Hash |
|---| ----------- | ------- | ----| --- |
| 1 | 2026-set-25 | Estácio - Curso Psicologia | documentos confidenciais com segurança-cleared.pdf](https://github.com/user-attachments/files/32658154/Como.enviar.documentos.confidenciais.com.seguranca-cleared.pdf) | 8120075a8796c31b739213af6bdd35c084e55469dc9bacb379729ef2fe42129d[Como enviar 
 | 

Como validar o hash (se o documento é original)

No Windows:
Faça o download do arquivos
No Windows, vá no menu iniciar, digite cmd e <ENTER>
No prompt de comando, certifique-se está na pasta onde o pdf for salvo, por exemplo Downloads (acesse esse pasta com comando "cd Downloads)
Digite esse comando para o item #1 da tabela:
certutil -hashfile "Como enviar documentos confidenciais com segurança-cleared.pdf" SHA256
No resultado, será gerado o número de hash, que deve bater com o hash informado na linha da tabela

