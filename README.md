# EstruturaDeDados


//Contrato
public interface Empilhavel //Stack ou Stackable
{
    //Operações Principais
    void empilhar(Object dado);     //push
    Object desempilhar();           //pop
    Object topo();                  //top
    void atualizar(Object dado);    //update

    //Operações Auxiliares
    boolean estaCheia();            //isFull       //Overflow
    boolean estaVazia();            //isEmpty      //Underflow
    String imprimir();              //print
}

// Métodos Básicos Estrutura de Dados (CRUDS)
//C -> Create (Criar)
//R -> Read (Ler)
//U -> Update (Atualizar)
//D -> Delete (Excluir)
//S -> Sort (Ordenar)


TIPOS DE DADOS

NUMÉRICO
    Inteiros
        tinyint, shortint
        int, uint
        longint, bigint
    Pontos Flutuantes
        Float
        Double
    Ponto Fixo (Numeric ou decimal)

CHAR
STRING (char[])

LÓGICO (bool, boolean)
    True, 1
    False, 0

VETOR (array, matriz unidimensional)
    array ordinal (indíce)
    array associativo (dicionário)

PONTEIRO

CONJUNTO //set (Vetor sem ordem)


# Estrutura De Dados

Repositório destinado ao estudo de estruturas de dados através da disciplina ofertada no 3º semestre do curso de BSI no IFBA - Campus Vitória da Conquista
