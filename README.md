Certamente, vou reescrever os dois trechos que você forneceu em Markdown:

```markdown
# Começando os Estudos em Java

O método `main` é o principal método em Java, e em Java, um programa é composto principalmente por métodos. Java é uma linguagem de programação fortemente tipada.

## Variáveis em Java

Ao lidar com variáveis em Java, é importante seguir algumas práticas. Por exemplo, iniciar uma aplicação com pacotes para diferenciar entre diferentes aplicações. O nome do pacote deve começar, por convenção, com letra minúscula.

Exemplo de método em classes:

```java
public class Inteiro {
    public static void main(String[] args) {
        // A lógica vem neste escopo
    }
}
```

Em Java, há uma palavra-chave para cada tipo de variável. Por exemplo:

- `int` para inteiro

## Dicas Importantes

Ao imprimir no console em Java, utilize o seguinte formato:

```java
System.out.println("Aqui vem o que você quer imprimir");
```

Não esqueça do ponto e vírgula (`;`), que é obrigatório em Java.

Algumas dicas de atalhos úteis:

- Digitar `Sysout` + `Ctrl` + `Tab` irá completar automaticamente o método sempre que estiver disponível.
- `Ctrl` + `S` para salvar.
- `Ctrl` + `F11` para executar o código.
- `Ctrl` + `D` para apagar uma linha inteira do código.

## Exemplo de Semântica de Variável

```java
int idade = 13;
```

Isso conclui o primeiro capítulo.
```

E o segundo trecho:

```markdown
# Variáveis do Tipo `float` e `double` em Java

Já sabemos que Java é uma linguagem fortemente tipada.

`double` é a palavra-chave para números flutuantes em Java.

Exemplo:

```java
double numero = 3.5;
double soma = numero + 2.8;
```

Java também aceita números inteiros em variáveis do tipo `double`, mas obrigatoriamente acrescenta 0 no resultado após o ponto decimal.

Exemplo:

```java
double numeroInteiro = 5;
// O resultado será 5.0
```

Isso conclui o segundo capítulo.
```



# Casting em Java

O casting em Java é utilizado para forçar a troca de tipagem de um número, geralmente convertendo um número flutuante para inteiro, de acordo com a decisão do programador.

Devido ao fato de Java ser uma linguagem fortemente tipada, ela lança exceções caso você queira realizar esse tipo de conversão. Um exemplo é quando tentamos atribuir um número real a uma variável inteira sem realizar o casting adequado:

```java
double salario = 2700.50;
int valor = salario; // Isso resultará em um erro de tipagem
```

Isso ocorre porque a variável `salario` é do tipo `double` (número real) e a tentativa de convertê-la para um inteiro resultaria na perda de dados.

Para forçar o Java a realizar a conversão mesmo assim, devemos utilizar o casting da seguinte forma:

```java
double salario = 2700.50;
int valor = (int) salario; // Realiza a conversão forçada
```

Neste exemplo, o `(int)` funciona como um operador de casting, semelhante a um `ToNumber` ou `ToString` em JavaScript.

Além do `double`, existem mais três tipos de variáveis para números em Java:

- **long:**
  
  ```java
  long numeroGrande = 535434443343453535L; // Para números muito grandes, acima de 2 terabytes
  ```

- **short:**
  
  ```java
  short numeroPequeno = 2133; // Para números menores
  ```

- **byte:**
  
  ```java
  byte numeroMuitoPequeno = 127; // Até somente 127 bytes
  ```

Lembre-se sempre de conferir as tipagens, pois o Java não permite riscos de erros relacionados a tipos.



