# token
Token
import java.util.*;
//https://www.jdoodle.com/online-java-compiler/
public class MyClass {
  public static void main(String args[]) {
    Token token = new Token();
	token.obtenerAlfabeto();

    }
}

class Token{
    private StringBuilder  sb;
	private String alfabeto;

    public void  obtenerAlfabeto(){
          sb = new StringBuilder();
          char x =  'A';
          while (x <='Z'){
              sb.append(x);
              x++;
          }// fin de while
          this.alfabeto = sb.toString();
    }//fin de metodo obtener alfabeto
  /*

	*/
  public String generarToken(){

    }//fin de metodo generarToken

}// fin
