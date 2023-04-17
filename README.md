# C/C++ToolBox
Construindo minha biblioteca de funções para C e C++

## Funções e suas respectivas assinaturas

### Função 1: Mensurando um arquivo
*Fonte - [StackOverFlow - Move the file pointer back after fseek]*(https://stackoverflow.com/questions/55777956/move-the-file-pointer-back-after-fseek)
~~~C++
/// @brief Recebe um ponteiro do tipo FILE e retorna o tamanho deste arquivo em caracteres
/// @return O tamanho de um arquivo em long int
long int SizeOfFile(FILE *PointerToFile)
~~~
