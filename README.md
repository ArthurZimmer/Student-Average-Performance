# Media-de-aproveitamento-e-conceito
Programa que faz a média de aproveitamento de um aluno de acordo com notas de atividades, juntamente da média de nota do aluno.

    using System;
    
    public class Atividade1
    {
        public static void Main(string[] args)
        {
            Console.WriteLine("Programa média de aproveitamento e conceito");

            Console.Write("\n\nDigite seu número de matrícula: ");
            int MATRICULA = int.Parse(Console.ReadLine());
    
            Console.Write("Digite a primeira nota: ");
            float N1 = float.Parse(Console.ReadLine());
    
            Console.Write("Digite a segunda nota: ");
            float N2 = float.Parse(Console.ReadLine());
    
            Console.Write("Digite a terceira nota: ");
            float N3 = float.Parse(Console.ReadLine());
    
            Console.Write("Digite a nota média de seus exercícios: ");
            float ME = float.Parse(Console.ReadLine());
            Console.Clear();
    
            float MA = (N1 + N2 * 2 + N3 * 3 + ME)/ 7;
            char CONCEITO;
            char RESULTADO;
    
            if (MA >= 90)
            {
                CONCEITO = 'A';
    
                Console.Write("Número de identificação do aluno: {0}\n", MATRICULA);
                Console.Write("Notas correspondentes do aluno: {0}, {1}, {2}.\n", N1, N2, N3);
                Console.Write("Média dos exercícios do aluno: {0}\n", ME);
                Console.Write("Média de aproveitamento do aluno: {0}\n", MA);
                Console.Write("O conceito obtido foi: {0}\n", CONCEITO);
                Console.Write("Resultado: APROVADO\n");
            } else if (MA >= 75 && MA < 90) {
                CONCEITO = 'B';
    
                Console.Write("Número de identificação do aluno: {0}\n", MATRICULA);
                Console.Write("Notas correspondentes do aluno: {0}, {1}, {2}.\n", N1, N2, N3);
                Console.Write("Média dos exercícios do aluno: {0}\n", ME);
                Console.Write("Média de aproveitamento do aluno: {0}\n", MA);
                Console.Write("O conceito obtido foi: {0}\n", CONCEITO);
                Console.Write("Resultado: APROVADO\n");
            } else if (MA >= 60 && MA < 75) {
                CONCEITO = 'C';
    
                Console.Write("Número de identificação do aluno: {0}\n", MATRICULA);
                Console.Write("Notas correspondentes do aluno: {0}, {1}, {2}.\n", N1, N2, N3);
                Console.Write("Média dos exercícios do aluno: {0}\n", ME);
                Console.Write("Média de aproveitamento do aluno: {0}\n", MA);
                Console.Write("O conceito obtido foi: {0}\n", CONCEITO);
                Console.Write("Resultado: APROVADO\n");
            } else if (MA >= 40 && MA < 60) {
                CONCEITO = 'D';
    
                Console.Write("Número de identificação do aluno: {0}\n", MATRICULA);
                Console.Write("Notas correspondentes do aluno: {0}, {1}, {2}.\n", N1, N2, N3);
                Console.Write("Média dos exercícios do aluno: {0}\n", ME);
                Console.Write("Média de aproveitamento do aluno: {0}\n", MA);
                Console.Write("O conceito obtido foi: {0}\n", CONCEITO);
                Console.Write("Resultado: REPROVADO\n");
            } else if (MA < 40) {
                CONCEITO = 'E';
    
                Console.Write("Número de identificação do aluno: {0}\n", MATRICULA);
                Console.Write("Notas correspondentes do aluno: {0}, {1}, {2}.\n", N1, N2, N3);
                Console.Write("Média dos exercícios do aluno: {0}\n", ME);
                Console.Write("Média de aproveitamento do aluno: {0}\n", MA);
                Console.Write("O conceito obtido foi: {0}\n", CONCEITO);
                Console.Write("Resultado: REPROVADO\n");
            }
      }
    }
