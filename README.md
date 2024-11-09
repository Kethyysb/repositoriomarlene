# O Treinador Determinado

class Treinador:
    def __init__(self, nome):
        self.nome = nome
        self.clientes = []

    def adicionar_cliente(self, cliente):
        self.clientes.append(cliente)

    def treinar(self, cliente):
        print(f"{self.nome} está treinando {cliente.nome}.")

class Cliente:
    def __init__(self, nome, objetivo):
        self.nome = nome
        self.objetivo = objetivo

    def alcançar_objetivo(self):
        print(f"{self.nome} alcançou seu objetivo: {self.objetivo}.")

# Criação do treinador e cliente
joao = Treinador("João")
pedro = Cliente("Pedro", "Perder peso e melhorar saúde")

# Adicionando cliente ao treinador
joao.adicionar_cliente(pedro)

# Treinamento
joao.treinar(pedro)

# Pedro alcança seu objetivo
pedro.alcançar_objetivo()


Este código define duas classes: Treinador e Cliente. O treinador João é criado e o cliente Pedro é adicionado a ele. Em seguida, João treina Pedro e Pedro alcança seu objetivo.
