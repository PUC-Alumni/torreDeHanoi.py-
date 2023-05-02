def torreDeHanoi(n, fonte = 'A', auxiliar = 'B', destino = 'C'): 
  if n == 1: 
    print("de", fonte, "para", destino)
  else:
    torreDeHanoi(n-1, fonte, destino, auxiliar) 
    print("de", fonte, "para", destino)
    torreDeHanoi(n-1, auxiliar, fonte, destino)
