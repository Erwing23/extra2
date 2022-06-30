# ejercicio de hilos


int pasajeros = N
int capacidad = C
int pasajeros_servidos=0
while (N != pasajeros_servidos){
	Coche coche = new Coche(); // Se crea un coche (El hilo inicia)
	while(coche.capacidad < capacidad){
		Pasajero pasajero = new Pasajero();// Aparece un pasajero (El hilo inicia)
        coche.subirpasajeros();
        pasajero.embarcarse(coche);
	}
    coche.encender();//Tiempo muerto hasta que el coche termine el viaje
    coche.bajarpasajeros()
    
    pasajeros_servidos += capacidad;



	
	
	
}



















