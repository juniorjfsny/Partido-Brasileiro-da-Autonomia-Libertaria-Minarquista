O erro confirma que o GitHub CLI (gh) não está instalado ou não está disponível no PATH do Windows. Por isso, os comandos gh --version e gh auth login não funcionam ainda.

Vamos resolver isso no PowerShell, dentro do seu projeto Partido-Brasileiro-da-Autonomia-Libertaria-Minarquista.
1. Instale o GitHub CLI
Primeiro, execute:

winget --version



Se aparecer a versão do Windows Package Manager, execute:

winget install --id GitHub.cli --exact



Se o Windows solicitar confirmação, autorize a instalação.
2. Verifique se a instalação funcionou
Quando o instalador terminar, feche o PowerShell e abra uma nova janela. Depois execute:

gh --version



Se aparecer um número de versão, prossiga com a autenticação:

gh auth login



A instalação pelo WinGet e a autenticação pelo navegador seguem o procedimento oficial do GitHub. 

GitHub
+1


 
3. Se o comando winget também não funcionar
Baixe o instalador oficial do GitHub CLI:

Baixar GitHub CLI para Windows.

Instale o programa, abra um novo PowerShell e repita a verificação.

Faça primeiro o teste winget --version e me diga o resultado. Assim saberemos se podemos instalar diretamente ou se precisamos corrigir o Windows Package Manager.




1. Execute este comando

winget install --id GitHub.cli --exact --source winget



Isso evita a consulta à fonte msstore durante essa instalação.
2. Após a instalação
Quando terminar, feche e abra novamente o PowerShell e execute:

gh --version



Se aparecer a versão do GitHub CLI, autentique-se:

gh auth login



Siga as instruções na tela para entrar na sua conta GitHub pelo navegador. 

Se aparecer outro erro durante a instalação, envie a mensagem completa aqui. Não precisa executar os comandos de autenticação até que gh --version funcione.