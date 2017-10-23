# EjerciciodeReposicion
## Walter Ruiz Erazo 1028916.

###Class Nodo:

int main()
{
   class Nodo
   {
    private string elemento;
    
    
    public void RecibirNodo()
    {
     Nodo *Sig;
     
     
     Nodo(string elemento)
     {
       this->elemento = elemento;
       sig = NULL;
     }
     string getElemento()
     {
        return elemento;    
     }
    }
    
    
   }
}




###Class ListaSimple: 


int main()
{
      class ListaSimple 
      {
          private string Nodo = *Primero;
          private string Nodo = *Ultimo; 
          
          public string ListaSimple()
          {
            primero = ultimo = null;
          }
          
          bool vacio()
          {
              return (primer = NULL);             
          }
          
          public void IngresarDatoInicio(string elemento)
          {
            Nodo *temp = new Nodo(elemento);
            if(vacio () == true)
            {
                primero = ultimo = temp;    
            }
            else
            {
                temp -> sig=primero;
                primero = temp;
            }
          }
          
          
          public IngresarDatoFinal(string elemeto)
          {
            Nodo *temp =  new Nodo (elemento);
            if(vacio() = true)
            {
                primero = ultimo = temp;    
            }
            else
            {
                ultimo -> sig = temp;
                ultimo = temp;
            }
          }
          
          public void MostrarLista()
          {
            if(vacio () = true)
            {
                cout<<"No hay elemento en la lista "<<endl;    
            }    
            else 
            {
                Nodo *aux = primero;
                int i = 1;
                cout<<"Los datos en la lista son los siguientes "<<endl;
                while (aux != NULL)
                {
                        cout<<"El elemento:" + <<i<< + "de la lista es:" + <<aux->getElemento()<<endl;
                        aux = aux -> sig;
                        i++;
                }
            }
          }
          
      }
}
