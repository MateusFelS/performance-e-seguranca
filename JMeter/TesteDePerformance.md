## 📊 Análise dos Resultados - 100 Usuários

| **Métrica**         | **Valor**  | **Significado** |
|---------------------|------------|----------------|
| **Número de amostras** | 200        | Total de requisições feitas (**100 usuários x 2 iterações**). |
| **Última amostra**  | 422 ms      | Tempo de resposta da última requisição feita. |
| **Média**          | 2223 ms     | Tempo médio de resposta (**2,2 segundos**). |
| **Desvio Padrão**  | 3059 ms     | Grande variação no tempo de resposta entre requisições. |

### Tabela de Resultados
<img src="https://github.com/user-attachments/assets/c809fb37-0fbb-4306-a9a2-cdac9db29a47" width="300">

---

## 📊 Análise dos Resultados - 500 Usuários

| **Métrica**         | **Valor**  | **Significado** |
|---------------------|------------|----------------|
| **Número de amostras** | 1000        | Total de requisições feitas (**500 usuários x 2 iterações**). |
| **Última amostra**  | 1524 ms     | Tempo de resposta da última requisição feita. |
| **Média**          | 3632 ms     | Tempo médio de resposta (**3,6 segundos**, aumento em relação ao teste anterior). |
| **Desvio Padrão**  | 2599 ms     | Ainda há variação, mas menor do que no teste anterior. |

### Tabela de Resultados
![image](https://github.com/user-attachments/assets/a418bdfe-999c-43eb-b5e4-cfaefa846d25)

## 📌 Comparação entre os testes
- **O tempo médio aumentou:** De 2,2s para 3,6s → Isso indica que o servidor está sobrecarregado com mais usuários.
- **Desvio padrão menor (3059ms → 2599ms):** Ainda há variação nos tempos de resposta, mas parece mais controlado.
- **Última amostra maior (422ms → 1524ms):** O tempo da última requisição também aumentou, sugerindo que o servidor está demorando mais conforme a carga aumenta.
