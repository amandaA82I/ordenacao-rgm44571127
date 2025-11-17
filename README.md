 Projeto: Comparação de Algoritmos de Ordenação  
 RGM: 44571127

Este projeto implementa e compara três algoritmos de ordenação em C:

- *Insertion Sort*
- *Merge Sort*
- *Quick Sort (Lomuto)*

São analisados:

- Número de comparações (cmp)
- Número de trocas/movimentações (swp)
- Tempo de execução em milissegundos

Todos os resultados são impressos em *formato CSV*.

---

RGM utilizado

RGM do aluno:



44571127


Convertido para vetor:



[4, 4, 5, 7, 1, 1, 2, 7]


Ordenado corretamente:



[1, 1, 2, 4, 4, 5, 7, 7]


---

compilação



gcc -O1 -std=c11 src/*.c -o ordena


---

Execução



./ordena


---

# ✔️ Contagem de passos

- 1 comparação = cmp++
- 1 troca/movimentação = swp++

---

 Medição de tempo

Tempo coletado com:



clock()


Cada caso é executado *5 vezes*, e a média é exibida.

---

 Exemplo de saída (RGM)



metodo,N,caso,passos_cmp,passos_swp,tempo_ms
insertion,8,rgm,22,17,0.003
merge,8,rgm,28,34,0.004
quick,8,rgm,18,16,0.002
