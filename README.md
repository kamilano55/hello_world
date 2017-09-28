public static void main(String[] args) {
        Scanner teclado = new Scanner(System.in);
        System.out.print("Digite o número de pernas: ");
        int pernas = teclado.nextInt();
        System.out.print("Isso é um(a) ");
        String tipo;
        switch (pernas){
            case 1:
                tipo = "Sací";
                break;
                //System.out.println("É um sací");
            case 2:
                tipo = "Bípedi";
                break;
                //System.out.println("");
            case 3:
                tipo = "tripé";
                break;
            case 4:
                tipo = "Quadrúpede";
                break;
            default:
                tipo = "ET";
                break;
    }
            System.out.println(tipo);
   
        
    }
    
}
