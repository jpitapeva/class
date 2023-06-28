# partial class

A palavra-chave partial indica que outras partes da classe, struct ou interface podem ser definidas no namespace. Todas as partes devem usar a palavra-chave partial. Todas as partes devem estar disponíveis em tempo de compilação para formar o tipo final. Todas as partes devem ter a mesma acessibilidade, tais como public, private e assim por diante.

----

# sealed class
Quando aplicado a uma classe, o modificador sealed impede que outras classes herdem dela. No exemplo a seguir, a classe B herda da classe A, mas nenhuma classe pode herdar da classe B.

C#

Copiar
class A {}
sealed class B : A {}


https://learn.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/partial-classes-and-methods

----
