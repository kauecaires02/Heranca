# Heranca
class Pessoa:
     def_init__(self.pNome,pIdade):
     self.nome = pNome
     self.idade = pIdade

class PessoaFisica(Pessoa):
    def __init__(self.pNome,pIdade,pCPF):
    Pessoa.__init__(self.pNome,pIdade)
    self.cpf = pCPF

    def andar(self):
      print("andando+")

      def comprar(self):
        print("comprando")


class PessoaJuridica(Pessoa):
def __init__(self.pNome.pIdade.pCNPJ):
super ().__init__(pNome,Idade)
self.cnpj = pCNPJ

pf = PessoaFisica("Maria",25,"123456")
pj = PessoaJuridica("Mercado", 15,"00100233")

print(pf.nome+" - "+str(pf.idade)+" - "+pf.cpf)
pf.andar()
pf.comprar
