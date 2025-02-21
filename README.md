# ProjetoForms1.Itensinformation
Criar as propriedades dos dados dos itens.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ProjetoForms1
{
    public class Itensinformation
    {
        //atalho propfull+tab tab
        private int codigo;

  public int Codigo
        {
            get { return codigo; }
            set { codigo = value; }
        }
        private int produto_codigo;

  public int Produto_codigo
        {
            get { return produto_codigo; }
            set { produto_codigo = value; }
        }
        private int vendas_codigo;

  public int Vendas_codigo
        {
            get { return vendas_codigo; }
            set { vendas_codigo = value; }
        }
        private int valorunitario;

  public int Valorunitario
        {
            get { return valorunitario; }
            set { valorunitario = value; }
        }
        private int quantidade;

  public int Quantidade
        {
            get { return quantidade; }
            set { quantidade = value; }
        }
        private int totalitens;

  public int Totalitens
        {
            get { return totalitens; }
            set { totalitens = value; }
        }

  }
}
