# EXAMEN-LAB
//EXAMEN 1 BUCLES
//YEGLIMAR ANDREA MONTANEZ MONTERO

#include  <iostream>
#include <stdlib.h>
#include <stdio.h>

using namespace std;


//ESTADISTICA  DE LA SECCIÓN:
//PROMEDIO: corte de notas de cada estudiante
//NÚMERO TOTAL DE ESTUDIANTES: Nro T de estudiantes en la seccion
//NÚMEROS DE ESTUDIANTES APPROBADOS: Nro de estudiantes A
//NÚMEROS DE ESTUDIANTES REPROBADOS: Nro de estudiantes R
//NÚMEROS DE NOTAS: nro de N
//SUMATORIA 1: Promedio de la sección
//SUMATORIA 2: Corte de notas de cada uno de los estudiantes 
//APRENDIZAJE: Evaluar cada uno de los estudiantes
//SWITCH: opcion
//VARIABLE: eleccion
//CORTES: Cortes de notas de los estudiantes
//NÚMEROS DE ESTUDIANTES SOBRESALIENTES: 19-20
//NÚMEROS DE ESTUDIANTES MUY BUENOS: 16-18
//NÚMEROS DE ESTUDIANTES BUENOS: 13-15
//NÚMEROS DE ESTUDIANTES REGULARES:10-12
//NUMERO  DE ESTUDIANTES MEJORABLES:6-10
//NÚMERO  DE ESTUDIANNTES DEFICIENTES:0-5

int main (){
	
	int nro t de estudiantes = 0, nro de estudiantes a = 0, nro de estudiantes r = 0, eleccion;
	int sobresalientes = 0, muy buenos = 0, buenos = 0, regulares = 0, mejorables =  0;
	int nro de N, mejorables=0, deficientes=0, opcion, i;
	float promedio, seccion, nota, sumatoria 1;
	float sumatoria 2, promedio = 0, aprendizaje
	char seccion	

        
        // Texto del menú que se verá cada vez
        
        printf("Menu de Opciones");
        printf("opcion 1: seccion, nota, promedio y estadisticas\n");
        printf("opcion 2: promedios y estadisticas\n");
        printf("ingrese una opcion");
        scanf("%d",opcion);
        
        
        switch(opcion)
		{
			//INGRESAR LA SECCION ANTES 
			
			
			case 1:
			{
					
			    prinft("ingresar la seccion correspondiente")
			    scanf("%c", &seccion); //ÚNICO CARÁCTER
			    
				
				
				
				do
            {

                printf("\ningresar las  notas del estudiante: ");
                scanf("%f", &nota);
                }

                if ((nota >= 0) && (nota < 5)){
                    nro de estudiantes r++; && nro de estudiantes deficientes++;
                }
                else if ((nota >= 6) && (nota < 10)){
                    nro de estudiantes r++; && nro de estudiantes mejorables++;
                }
                else if ((nota >= 10) && (nota < 13)){
                    nro de estudiantes a++; && nro de estudiantes regulares ++;
                }
                else if ((nota >= 13) && (nota < 16)){
                    nro de estudiantes a++; && nro de estudiantes buenos ++;
                }
                else if ((nota >= 16) && (nota < 19)){
                    nro de estudiantes a++; && nro de estudiantes mejorables;
                }
                else if ((nota >= 19) && (nota <= 6)){
                    nro de estudiantes a++; && nro de estudiantes sobresalientes++;
                }

                sumatoria 2 += corte de notas; nro de estudiantes++;
                prinft("calculando..\n")
                printf("quieres seguir calculando? Si=1, No=2\n");
                scanf("%d", &eleccion);
            }while (eleccion == 1);
			prinft("todo calculado");
			
			//ALMACENADOR
			
			prinft("\tNumero total de estudiantes");
			prinft("\tNumero  de estudiantes A");
			prinft("\tNumero  de estudiantes R");
			promedio_seccion = sumatoria 1/nro T de estudiantes
			rintf("\tNumero de estudiantes sobresalientes: %d\n", nro de estudiantes bresalientes);
            printf("\tNumero de estudiantes muy buenos: %d\n", nro de estudiantes muy buenos);
            printf("\tNumero de estudiantes buenos: %d\n", nro de estudiantes buenos);
            printf("\tNumero de estudiantes regulares: %d\n", nro de estudiantes regulares);
            printf("\tNumero de estudiantes mejorables: %d\n", nro de estudiantes mejorables);
            printf("\tNumero de estudiantes deficientes: %d\n", nro de estudiantes deficientes);
            printf("Seccion: %c\n", seccion);
            break;		
		
			}
			
			//VOLVER A INGRESAR LA SECCION Y NUMERO DE NOTAS 
			
			
			case 2:{
				
				
            printf("\ningresar el numero de notas: ");
            scanf("%d", &notas);

            printf("\ningresar la seccion: ");
            scanf("%c", &seccion);

            do
            {

                sumatoria 2 = 0; 
                
                
                for(i = 1; i <= nro de notas; i++){
                	
                    printf("ingresar la nota: ");
                    scanf("%f", &aprendizaje);
                    sumatoria 2 += aprendizaje;
                }
                promedio = sumatoria 2/ nro de notas;
                nota = promedio;
                while((nota < 0) (nota > 20)){
                    sumatoria 2 = 0;
                    
                    
                    printf("ingresar otra vez las notas\n");
                    for(i = 1; i <= nro de notas; i++){
                        printf("ingresar las notas: ");
                        scanf("%f", &aprendizaje);
                        sumatoria 2 += aprendizaje;
                    }
                    promedio = sumatoria 2/ nro de notas;
                    promedio = nota;
                }
                if ((nota >= 0) && (nota < 5)){
                    nro de estudiantes R++; && nro de estudiantes deficientes++;
                }
                else if ((nota >= 6) && (nota < 10)){
                    nro de estudiantes R++; && nro de estudiantes mejorables++;
                }
                else if ((nota >= 10) && (nota < 13)){
                    nro de estudiantes A++; && nro de estudiantes regulares ++;
                }
                else if ((nota >= 13) && (nota < 16)){
                    nro de estudiantes A++; && nro de estudiantes buenos ++;
                }
                else if ((nota >= 16) && (nota < 19)){
                    nro de estudiantes A++; && nro de estudiantes mejorables;
                }
                else if ((nota >= 19) && (nota <= 6)){
                    nro de estudiantes A++; && nro de estudiantes sobresalientes++;
                }
                sumatoria 1+= nota; nro de estudiantes++;
                
                
               prinft("calculando..\n")
                printf("quieres seguir calculando? Si=1, No=2\n");
                scanf("%d", &eleccion);
            }while (eleccion == 1);
			prinft("todo calculado");
			
			prinft("\tNumero total de estudiantes");
			prinft("\tNumero  de estudiantes A");
			prinft("\tNumero  de estudiantes R");
			promedio_seccion = sumatoria 1 /nro T de estudiantes
			rintf("\tNumero de estudiantes sobresalientes: %d\n", nro de estudiantes bresalientes);
            printf("\tNumero de estudiantes muy buenos: %d\n", nro de estudiantes muy buenos);
            printf("\tNumero de estudiantes buenos: %d\n", nro de estudiantes buenos);
            printf("\tNumero de estudiantes regulares: %d\n", nro de estudiantes regulares);
            printf("\tNumero de estudiantes mejorables: %d\n", nro de estudiantes mejorables);
            printf("\tNumero de estudiantes deficientes: %d\n", nro de estudiantes deficientes);
            printf("Seccion: %c\n", seccion);
            break;
	        }
	        
	        
	        
	        return 0;
        }
