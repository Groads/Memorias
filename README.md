# Memorias
Memoria Dinamica
class MemoriaDinamica:
    def main(self):
        frutas = []  
        frutas.append("Mango")  
        frutas.append("Manzana")  
        frutas.append("Banana")  
        frutas.append("Uvas") 
        print(frutas)  

        frutas.pop(0)  
        frutas.pop(1)  
        frutas.insert(1, "Piña")  
        print(frutas)  


memoria_dinamica = MemoriaDinamica()  
memoria_dinamica.main()  


Memoria Estatica
class MemoriaEstatica:
    def main(self):
        calificaciones = [0] * 5  
        for i in range(5):
            calificaciones[i] = int(input("Ingrese la calificación: "))


memoria_estatica = MemoriaEstatica()
memoria_estatica.main()
