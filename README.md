# Introducao-a-variaveis-com-java


                                                                    Introdução a Variávels


.O que são variáveis
.Como declarar variáveis
.Convenção de nomenclatura
.Tipos primitivos

                                                                       O que é variável

EX:A gente precisa no nosso dia a dia quardar arquivos, então um exemplo você foi a uma festa você fez uma viagem você tirou várias fotos, e você quer
quardar essas fotos, então você vai utilizar algum dispositivo alguma área de memória para quardar essas fotos seja no cartão, seja em um USB, seja no HD do
computador, ou por exemplo se você tiver algum MP4 ou algum dispósitivo que toca música vídeo, que também aceita que você use ele como pen-drive, então no
nosso dia a dia a gente já usa vários objetos e dispositivos que servem para a gente poder quardar alguma coisa o valor de alguma coisa, e como é que
funciona isso, quando você ta ali no seu computador e você quica no arquivo do seu curriculo aquele arquivo na verdade ele ta fazendo só referencia a uma
área da memória do seu computador seja do seu HD ou seja no pen-drive, em qualquer dispositivo que você possa quardar arquivos, então aquele ícone que as
vezes você vê no seu computador na verdade é uma referencia para uma área de memória do seu HD ou do díspositivo que você ta quardando aquele arquivo.
 Então uma variável em um programa seria uma referencia a uma área de memória que vai quardar algum valor,exemplo quando a gente tá fazendo um programa
e você precisa quardar a idade de uma pessoa ou um nome de uma pessoa você precisa quardar um valor para que você utilize depois esse valor no programa
a gente quarda todos esses valores dentro de uma variável.

                                                                         O que é variável

.Área de memória associada a um nome, que pode armazenar valores de um determinado tipo

EX:Se você precisa quardar um nome da pessoa em tão você pode ter uma variável chamada nome ou se você quiser ser um pouco mais especifico nome da pessoa
ou idade da pessoa, então você tem essa variável que tem um nome e essa variável vai estar associada vai fazer uma referencia para uma área da memória
onde você vai armazenar o nome da pessoa a idade da pessoa, o valor que você quiser.

.Exemplo:armazenar idade de uma pessoa

                                                                Como declarar uma variável em java

.<tipo> <nome da variável>;

.<tipo> <nome da variável> = <valor>;

                                                                     Convenção Nomenclatura

.<tipo> <nome da variável>;

.<tipo> <nome da variável> = <valor>;

O que a gente pode dar de nome para uma variável.

O que você não pode dar de nome para uma variável.

                                                                      Palavras reservadas

                                    __________________________________________________________
                                    |          |          |          |          |            |
                                    | abstract | continue |   for    |   new    |   switch   |
                                    |__________|__________|__________|__________|____________|
                                    |          |          |          |          |            |
                                    |  assert  | default  |  goto    | package  |synchronized|
                                    |__________|__________|__________|__________|____________|
                                    |          |          |          |          |            |
                                    | boolean  |    do    |    if    |  private |    this    |
                                    |__________|__________|__________|__________|____________|
                                    |          |          |          |          |            |
                                    |  break   | double   |implements| protected|    throw   |
                                    |__________|__________|__________|__________|____________|
                                    |          |          |          |          |            |
                                    |   byte   |  else    |  import  |  public  |   throws   |
                                    |__________|__________|__________|__________|____________|
                                    |          |          |          |          |            |
                                    |   case   | enum     |instanceof| return   |  transient |
                                    |__________|__________|__________|__________|____________|
                                    |          |          |          |          |            |
                                    |   catch  | extends  |   int    |  short   |     try    |
                                    |__________|__________|__________|__________|____________|
                                    |          |          |          |          |            |
                                    |   char   |  final   | interface|  static  |     void   |
                                    |__________|__________|__________|__________|____________|
                                    |          |          |          |          |            |
                                    |   class  | finally  |   long   | strictfp |  volatile  |
                                    |__________|__________|__________|__________|____________|
                                    |          |          |          |          |            |
                                    |   const  |  float   |   native |  super   |    while   |
                                    |__________|__________|__________|__________|____________|


                                                                     Convenção Nomenclatura

.a-z A-z_&

.a-z A-z_& 0-9

.camelCase

                                                                        Tipos primitivos

.int             .float            .char

Nos tipos primitivos você tem tipos inteiros, que são os números inteiros tanto negativo e positivo que a gente representa como o int, que a gente tem como
exemplo o float e o double que seriam os pontos flutuantes que seriam os números que tem vírgula, como 5,45 a gente também tem caracteres que apresentando
por exemplo a letra A, a letra b, a letra c, e adiante, a gente tem caracteres que representa parte do char, também tem o boolean que seriam os valores de
A positivo ou falso, mais isso iremos ver na próxima explicação.

A string não é um tipo primitivo e sim uma classe.


package com.madu.variaveis;

public class VariaveisTeste1 {

	public static void main(String[] args) {
		
		 //convenção Java
		 int idade = 14;
		 String nome = "Madu";
		 String nomeDoMeuCachorro = "kiki";
		 String ano2014 = "2014";
		 
		 //aceito, mas não é utilizado
		 int _idade;
		 int $idade;
		 
		 //não é convenção java
		 String nome_do_meu_cachorro;
		 String NomeDoMeuCachorro;
		 
		 idade = 25;
		 
		 System.out.println("Idade = " + idade);
		 System.out.println("Nome = " + nome);
		 
		 //má prática
		 int a = 10;
		 String b = "Madu";
	}

}
