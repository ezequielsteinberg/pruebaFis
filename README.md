# pruebaFis

 public boolean estadisticaMejora (int[][] mat){
    int crecio=0; 
    fila=0;  
    whie (fila<mat.length){
 for(int i=0;i<mat[0].length;i++){
        if(mat[fila][i]<mat[fila][i+1]){
            crecio++;
        }
    }
    fila ++;
for(int i=mat[0].length;i<0;i--){
if(mat[fila][i]<mat[fila][i-1]){
            crecio++;
        }
}
 fila ++;
 }
 return (mat[0].length * mat.length -1) >= crecio;
    }
   

    