### 🌉️ The Bridge

Desenvolvido para aplicação geral em treliças 2D.

A solução do sistema de equações utiliza técnicas numéricas (Método de Jacobi e/ou Gauss-Seidel).

Siga o jupyter notebook `report.ipynb`. Para entender mais sobre a proposta do projeto leia o arquivo `report.pdf`.

#### 📌️ Exemplo de aplicação

<div align="center">
    <img alt="exemplo" src="https://github.com/leticiacb1/TheBridge/raw/main/img/exemplo.png" width="300rm" \>
</div>

Nesse exemplo, cada barra possui uma área de seção transversal $A = 2 \cdot 10^{-4} m²$ e $E = 210GPa$.

A carga pontual aplicada ao nó três na direção $y$ é $P_y = −100N$. 

Na direção $x$ a carga pontual aplicada é igual a $P_x=150N$. 

A tensão última a tração e compressão são iguais a $sigma_{tracao} = \sigma_{compressao} = 1570 \cdot 10⁶ Pa$. 

`exemplo de arquivo de entrada`

<div align="center">
    <img alt="entrada" src="https://raw.githubusercontent.com/leticiacb1/TheBridge/main/img/entrada.png?token=GHSAT0AAAAAACN4HAT65OJTL7TLT7B54XPAZP4Z2RQ" width="300rm" \>
</div>
<br>

`exemplo de arquivo de saída`

<div align="center">
    <img alt="saida" src="https://github.com/leticiacb1/TheBridge/blob/main/img/saida.png" width="100rm" \>
</div>
<br>

<div align="center">
    <img alt="grafico" src="https://github.com/leticiacb1/TheBridge/blob/main/img/grafico.png" width="400rm" \>
</div>

#### ⚙️ Protótipo real

Após simulações físicas realizadas nesse projeto, foi também feito um modelo em MDF de uma ponte. Esse modelo deveria aguentar no mínimo 150 N de força.

<div align="center">
    <img alt="ponte" src="https://github.com/leticiacb1/TheBridge/raw/main/img/ponte.jpg" width="400rm" \>
    <img alt="ponte testada" src="https://github.com/leticiacb1/TheBridge/raw/main/img/teste_ponte.jpg" width="200rm" \>
</div>
