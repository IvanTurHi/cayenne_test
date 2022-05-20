# cyaenne_test

# Ссылка на ноутбук
https://colab.research.google.com/drive/18fCG49N3CPBxYIdQQHqV6W3kvUU7HTWx?usp=sharing


# Результаты тестов

|  | direct | tau_leaping | tau_adaptive |
| :---: | :---: | :---: | :---: |
| max_t=100, max_iter=100 | 197ms/2303940085  | 204ms/2303940085 | 204ms/2303940085 |
| max_t=1000, max_iter=1000  | 203ms/2303940085 | 524ms/2303940085 | 199ms/2303940085  |
| max_t=10000, max_iter=10000 | 721ms/2094122177 | 3.72s/2239406247 | 706ms/2303940085  |
| max_t=100000, max_iter=100000 |6.62s/2042692346 | 35.5s/1410082288 | 5.33s/2042692346 |
| max_t=1000000, max_iter=1000000 | 65s/1385255593b | Память закончилась(лимит12Гб) | 51.1s/219502016 |
| max_t=10000000, max_iter=10000000 | Память закончилась(лимит12Гб) | - | 8m 27s/888043726 |

# Ссылка на статью авторов cyaenne
https://www.biorxiv.org/content/10.1101/2020.10.10.334623v1.full.pdf
