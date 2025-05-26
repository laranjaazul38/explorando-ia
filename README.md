# explorando-ia
class MissaoIA:
    def __init__(self, objetivo, impacto, desafios):
        self.objetivo = objetivo
        self.impacto = impacto
        self.desafios = desafios

    def exibir_missao(self):
        print("🌍 Missão: Desenvolver inteligência artificial para um futuro mais eficiente e ético.")
        print(f"🎯 Objetivo: {self.objetivo}")
        print(f"⚡ Impacto: {self.impacto}")
        print("🚧 Desafios:")
        for desafio in self.desafios:
            print(f"- {desafio}")

# Definição da missão
objetivo = "Criar sistemas inteligentes que melhorem a vida das pessoas."
impacto = "Automação, tomada de decisões, inovação em diversas áreas."
desafios = [
    "Ética na IA",
    "Privacidade dos dados",
    "Viés algorítmico",
    "Segurança cibernética"
]

# Instanciar a missão e exibi-la
missao = MissaoIA(objetivo, impacto, desafios)
missao.exibir_missao()
