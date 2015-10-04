# TP-10
Facundo Castellano - K2051
* **Dada la siguiente unidad de traducción:**

        int printf(const char*, ...);
        int main(void){
          int _[:>=<%-!.0,};
          printf("%d%d", sizeof _-sizeof _[0], sizeof(char)+0[_]);
        }
        
* **Análisis Léxico**
  * Investigue sobre digraphs y trigraphs.
  * Responda: ¿Cuándo se reeemplazanlos trigraphs? ¿Y los digraphs?
  * Escriba la secuencia de lexemas a partir de la secuencia de caracteres.
  * Tokenize" (i.e., escriba la secuencia de tokens) a partir de la secuencia de lexemas.
  * Indique si la UT es léxicamente correcta.
   
* **Análisis Sintáctico**
  * Arme el árbol de derivación, a partir de la secuencia de tokens.  Lea sobre BNF y busque el BNF de unidad de         traducción en [K&R1988]A.13. Las reglas destacadas: declaración, incializador, y expresión.
  * Indique si la UT es sintácticamente correcta.
  
* **Análisis Semántico**
  * Indique si la UT es léxicamente correcta. ¿Viola alguna restricción semántica?
  * Si es semánticamente correcto, indique qué hace el programa, responda por partes:
  declaraciones, expresiones, y sentencias. Temas destacados: arreglos, sizeof, incialización, y
  conversiones automáticas.
  * Si es semánticamente correcto, indique la salida. Justifique.
  
