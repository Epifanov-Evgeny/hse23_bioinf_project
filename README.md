# hse23_bioinf_project

### Описание белка
[Here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7314539/), we demonstrate that Zcwpw1 is an H3K4me3 reader that is required for DSB repair and synapsis in mouse testes.

В белке ZCWPW1 наблюдаются домены PWWP super family(3), zf-CW super family.
Экспрессия: Testis(144.0)

## Выравнивания

H2A
![image](https://github.com/Epifanov-Evgeny/hse23_bioinf_project/assets/87313319/d5f56237-8d18-43dc-b81a-bd526887ee88)
H2B
![image](https://github.com/Epifanov-Evgeny/hse23_bioinf_project/assets/87313319/1736ea4f-4da8-409c-9278-d6378e595326)
H3
![image](https://github.com/Epifanov-Evgeny/hse23_bioinf_project/assets/87313319/a8caf62e-2667-421d-b792-05d6f905d2ab)
H4
![image](https://github.com/Epifanov-Evgeny/hse23_bioinf_project/assets/87313319/fa258d96-fdaf-4fbf-8f09-70a729f807e5)

Различия между белками в гистонах H3 и H4 незначительны, существует некоторое количество полиморфизма. В то же время, белки в других гистонах также отличаются, но их различия все равно не настолько значительны.

## Таблицы
e_value
|        |    human |    mouse |   zebrafish |   drosophila |   c.elegans |   ciliate |    yeast |   methanocaldococcus |   thermococcus |   e.coli |   tuberculosis |
|:-------|---------:|---------:|------------:|-------------:|------------:|----------:|---------:|---------------------:|---------------:|---------:|---------------:|
| H2A    | 4.94e-91 | 4.57e-84 |    1.06e-81 |     2.34e-69 |    6.53e-67 |  2.45e-57 | 8.88e-63 |             0.001    |       0.15     |      1   |          0.4   |
| H2B    | 2.85e-87 | 1.15e-83 |    1.85e-71 |     3.3e-59  |    5.28e-65 |  1.91e-49 | 3.07e-57 |             1        |       0.17     |      1   |          1     |
| H3     | 2.19e-96 | 1.54e-96 |    1.77e-95 |     9.39e-96 |    4.46e-94 |  8.41e-86 | 3.31e-87 |             0.034    |       0.057    |      0.9 |          1     |
| H4     | 1.09e-67 | 7.6e-68  |    1.13e-68 |     8.02e-68 |    6.15e-68 |  1.96e-45 | 1.08e-52 |             8.22e-05 |       3.31e-05 |      1   |          0.069 |
| ZCWPW1 | 1e-300   | 1e-300   |    2.52e-11 |     1.11e-05 |    0.042    |  0.014    | 0.002    |             1        |       1        |      1   |          1     |

-log(e_value)
|        |    human |    mouse |   zebrafish |   drosophila |   c.elegans |   ciliate |    yeast |   methanocaldococcus |   thermococcus |    e.coli |   tuberculosis |
|:-------|---------:|---------:|------------:|-------------:|------------:|----------:|---------:|---------------------:|---------------:|----------:|---------------:|
| H2A    |  90.3063 |  83.3401 |     80.9747 |     68.6308  |    66.1851  |  56.6108  | 62.0516  |              3       |       0.823909 | 0         |        0.39794 |
| H2B    |  86.5452 |  82.9393 |     70.7328 |     58.4815  |    64.2774  |  48.719   | 56.5129  |              0       |       0.769551 | 0         |        0       |
| H3     |  95.6596 |  95.8125 |     94.752  |     95.0273  |    93.3507  |  85.0752  | 86.4802  |              1.46852 |       1.24413  | 0.0457575 |        0       |
| H4     |  66.9626 |  67.1192 |     67.9469 |     67.0958  |    67.2111  |  44.7077  | 51.9666  |              4.08513 |       4.48017  | 0         |        1.16115 |
| ZCWPW1 | 300      | 300      |     10.5986 |      4.95468 |     1.37675 |   1.85387 |  2.69897 |              0       |       0        | 0         |        0       |


Heatmap: 

![image_2023-06-11_23-29-49](https://github.com/Epifanov-Evgeny/hse23_bioinf_project/assets/87313319/a6e8c1d1-0da9-4792-80ab-a7f5b77a59c2)

Вывод: Разность длин данного белка и его гомолога меньше всего для Mouse, а для zebrafish разность слишком большая, и он не может считаться гомологом. Эволюционно ген появился в Mouse (позвоночные)
