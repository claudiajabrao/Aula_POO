# Onboarding GitHub e Codespaces
## Programação Orientada a Objetos - Java

### 1. Criar uma conta no GitHub
1. Acesse https://github.com/signup
2. Informe seu e-mail.
3. Crie um nome de usuário e uma senha.
4. Confirme o cadastro e entre no GitHub.

### 2. Criar um repositório
1. Clique em New repository.
2. Informe o nome do repositório.
3. Escolha Public ou Private.
4. Marque Add a README file.
5. Clique em Create repository.

### 3. Criar um Codespace
1. Abra o repositório.
2. Clique no botão Code.
3. Selecione Codespaces.
4. Clique em Create codespace on main.
5. Aguarde a abertura do editor.

### 4. Configurar o Java
1. Abra a área Extensions.
2. Procure Extension Pack for Java.
3. Instale a extensão da Microsoft.
4. Mantenha a atualização automática ativada.
5. Se solicitado, habilite Standard Mode.

### 5. Verificar o Java
Abra Terminal > New Terminal.

Execute:

    java -version
    javac -version

### 6. Criar o primeiro programa
Crie o arquivo OlaMundo.java:

```java
public class OlaMundo {
    public static void main(String[] args) {
        System.out.println("Ola, mundo!");
    }
}
```

### 7. Compilar e executar
No terminal, digite:

```bash
javac OlaMundo.java
java OlaMundo
```

Também é possível usar Run no editor.

### 8. Organizar os programas
Crie uma pasta para cada aula.

Mantenha juntas as classes Java que fazem
parte de um mesmo exemplo.

### 9. Salvar o programa no GitHub
No terminal, execute:

```bash
git status
git add .
git commit -m "Adiciona programas da aula"
git push
```

Explicação:
- git status: verifica as alterações.
- git add: prepara os arquivos.
- git commit: registra uma versão.
- git push: envia as alterações ao GitHub.

### 10. Consultar e atualizar o projeto
- Consulte os arquivos no repositório GitHub.
- Use git pull para integrar alterações remotas.
- Use git status para verificar arquivos modificados.
- Faça commits ao concluir cada atividade.

### 11. Encerrar o Codespace
1. Acesse https://github.com/codespaces
2. Localize seu Codespace.
3. No menu de opções, selecione Stop codespace.

Importante: fechar a aba do navegador não
interrompe imediatamente o Codespace.
