# Disciplina: Linguagem de Programação I - IFBA Euclides da Cunha

## PROVA DE RECUPERAÇÃO - UNIDADE 1

### Entrega até 23/09/2021 às 23:59

### **Implementar os seguintes requisitos**

- Acrescente mais dois tipos de atributos na classe Produto, a seu critério,
  como por exemplo, um atributo para armazenar o preço de custo e outro para
  armazenar o preço de venda, usando encapsulamento.
- Acrescente um método na classe Produto para calcular o lucro do produto,
  que deve ser o preço de venda menos o preço de custo.
- Crie uma classe RepositórioPedidos que armazene os pedidos de um supermercado.
  Essa classe deve ser capaz de gerar um relatório de vendas do dia.
- A classe principal deve ser capaz de adicionar mais de um pedido, calcular o
  valor total de cada pedido e gerar o relatório de vendas ao final do di, incluíndo
  lucro adquirido.

Questão 1e2 

public class Produto { 
Scanner calc = New Scanner (System.in)
private String nome; 
private double preco; 
private int  quantidadeEstoque; 
private double precoCusto:
private double precoVenda;
public Produto(String nome, double preco, int quantidade, double custo, double venda) { 
this.nome = nome; 
this.preco = preco; 
this.quantidadeEstoque = quantidade;
this.precoCusto = custo;
this.precoVenda = valor;
} 
public String getNome() { 
return this.nome; 
} 
public double getPreco() { 
return this.preco; 
} 
public int getQuantidade() { 
return this.quantidadeEstoque;
} 
public double getCusto(){
return this.precoCusto;
}
public void setCusto(int Custo) {
this.precoCusto = Custo;
}
public double getValor(){
return this.precoVenda;
}
public void setValor(double Valor) {
this.precoVenda = Valor;
} 

float lucro; 

Calclucro(){ 

Lucro = precoValor - precoCusto; 

System.out.println ("O obtido lucro é:" + lucro); 

}
