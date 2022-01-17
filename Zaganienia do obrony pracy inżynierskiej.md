# Zaganienia na egzmin inżynierski

## Podstawy automatyki

#### Modele układów dynamicznych - równania stanu wyjścia, transmitancja operatorowa

$$
\begin{cases}
\dot{x}(t)=Ax(t)+bu(t), \quad \quad x(0)=x_0  \\
y(t)=c^Tx(t) + du(t)
\end{cases}
$$

- Trasmitancja - jest to funkcja charakteryzująca włosności dynamiczne układu liniowego . Określ zależność pomiędzy sygnałem wejściowym, a wyjściowym układu. 
  
  - **<u>Transmitancje pełna</u>** - daje podstawy do orzekania stabilności układu na podstawie **M(s)**, które jest wielomianem charakterystycznym macierzy **A**. Ponieważ w mianowniku transmitancji minimalnej nie występują wszystkie wartości własne układu, to nie daje ona podstawy do stwierdzenia stabilności, nawet gdy wszystkie bieguny leżą w lewej płaszczyźnie. Natomiast, gdy istnieje co najmniej jeden biegun w dodatniej części rzeczywistej, to układ jest niestabilny. 
  
  - <u>**Trasmitancja minimalna**</u> - jest wystarczająca do wyznaczenia zależności wejściowo-wyjściowych oraz składowej wymuszonej odpowiedzi oraz jest podstawą do wyznaczenia charakterystki wyjściowo-wejściowej. 
    
    Wzór na transmitancję minimalną:
    
    $K(S)=\frac{\displaystyle\sum_{i=0}^{m^t} b_is^i}
    {{\displaystyle\sum_{i=0}^{n^t} b_is^i}} = 
    \frac{b_m\displaystyle\prod_{i=0}^{m^t}(s-z_i)}
    {\displaystyle\prod_{i=1}^{n^t}(s-p_i)}$

          $m'=m-k$

          $n'=n-k$, gdzie $k$ - liczba pokrywających się zer i biegunów

          $z_i$ - zera

          $p_i$ - bieguny

      

- Gdy część zer pokrywa się z biegunami wyrażenia, to po skróceniu czynników licznika i mianownika wyrażenie to nazywa się **transmitancją minimilną**. Opisuja ona część sterowalną i obserwowalną układu, a zatem składową wymuszeń rozwiązań. 

- **Transmitancja pełna** opisuje także składową swobodną, uwzględniając część sterowalną i nieobserwowalną.  

#### Charakterystki częstotliwościowe - rodzaje, interpretacja

1. Charakters
