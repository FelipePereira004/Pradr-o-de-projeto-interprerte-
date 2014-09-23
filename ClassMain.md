Pradr-o-de-projeto-interprerte-
===============================
package testeapre;

import javax.swing.JOptionPane;

public class Tela {
	 static Nomes nome= new Nomes();
	 static int num;

	public static void main(String[]args){
		
		
		
		
		num=Integer.parseInt(JOptionPane.showInputDialog(null,"Informe numero de 1 a 10 para se obter numeral romano"));
		
		teste();
		
		
		
	}
	
	static 	public void teste(){
		if(num==1){
			JOptionPane.showMessageDialog(null,"numero 1 em romano: "+nome.GetI());
		}else{
			if(num==2){
				
				JOptionPane.showMessageDialog(null,"numero 2 em romano: "+nome.GetII());
			}else{
				if(num==3){
					JOptionPane.showMessageDialog(null,"numero 3 em romano: "+nome.GetIII());
				}else{
					if(num==4){
						JOptionPane.showMessageDialog(null,"numero 4 em romano: "+nome.GetIV());
					}else{
						if(num==5){
							JOptionPane.showMessageDialog(null,"numero 5 em romano: "+nome.GetV());
						}else{
							if(num==6){
								JOptionPane.showMessageDialog(null,"numero 6 em romano: "+nome.GetVI());
							}else{
								if(num==7){
									JOptionPane.showMessageDialog(null,"numero 7 em romano: "+nome.GetVII());
								}else{
									if(num==8){
										JOptionPane.showMessageDialog(null,"numero 8 em romano: "+nome.GetVIII());
										
									}else{
										if(num==9){
											JOptionPane.showMessageDialog(null,"numero 9 em romano: "+nome.GetIX());
										}else{
											if(num==10){
												JOptionPane.showMessageDialog(null,"numero 10 em romano: "+nome.GetX());
												
											}
										}
									}
								}
							}
						}
					}
				}
			}
		}
	}
}




