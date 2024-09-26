1. Sintaxe básica.
    1.1. Estrutura de um programa C#.
        1.1.1. Namespace.
            Define um escopo que contém um conjunto de objetos relacionados.

            ```csharp
            namespace MeuPrograma
            {
                // Código do programa
            }           
            ```
        1.1.2. Classe.
            A unidade básica de encapsulamento de dados e métodos.

            ```csharp
            public class Program
            {
                // Métodos e propriedades
            }       
            ```

        1.1.3. Main.
            O ponto de entrada de um programa C#.

            ```csharp
            public static void Main(string[] args)
            {
                // Código a ser executado
            }
            ```        

        1.1.4. Comentários.
            Usados para documentar o código.

            ```csharp
            // Este é um comentário de linha única
            /*
            Este é um comentário de múltiplas linhas
            */
            ``` 

        1.1.5. Diretivas using.
            Importam namespaces que contêm classes e métodos que você deseja usar no programa.

            ```csharp
                using System;
            */
            ``` 

        1.1.6. Exemplo completo.

        ```csharp
        using System;

        namespace MeuPrograma
        {
            public class Program
            {
                public static void Main(string[] args)
                {
                    Console.WriteLine("Hello, World!");
                }
            }
        }
        ```

    1.2. Tipos de dados primitivos (int, string, bool, etc.).

    1.3. Operadores (aritméticos, lógicos, relacionais).

2. Estrutura de Controle
    2.1. Condicionais (if, else, switch).
    2.2. Laços (for, while, foreach).

3. Classes e Objetos
    3.1. Definição de classes e criação de objetos.
    3.2. Construtores e destrutores.
    3.3. Modificadores de acesso (public, private, protected).

4. Herança e Polimorfismo
    4.1. Conceitos de herança.
    4.2. Métodos virtuais e sobrescritos.
    4.3. Interfaces e classes abstratas.

5. Coleções e Generics
    5.1. Arrays e listas (List<T>).
    5.2. Dicionários (Dictionary<TKey, TValue>).
    5.3. Uso de generics para criar classes e métodos reutilizáveis.

6. Tratamento de Exceções
    6.1. Uso de try, catch, finally.
    6.2. Criação de exceções personalizadas.

7. LINQ (Language Integrated Query)
    7.1. Consultas LINQ para manipulação de coleções.
    7.2. Métodos de extensão LINQ (Select, Where, OrderBy).

8. Delegates e Eventos
    8.1. Definição e uso de delegates.
    8.2. Criação e manipulação de eventos.

9. Programação Assíncrona
    9.1. Uso de async e await.
    9.2. Tarefas (Task e Task<T>).

10. Manipulação de Arquivos e I/O
    10.1. Leitura e escrita de arquivos.