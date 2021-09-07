# TokenVersionSwap
TokenVersionSwap es un swap que nos permite intercambiar un token por otro.

Los tokens del swap se definirán al crear el contrato, al igual que el rate entre esos tokens, el rate va definido en porcentaje. Ej: Si 1 TokenV1 equivale a 1 TokenV2, 
sería 'rate = 100' (100%).

Al hacer el swap los tokens de la versión 2 quedarán retenidos en el contrato, y solo se podrá hacer claim de los tokens 1 vez cada X tiempo, permitiendo retirar el 25% de tu balance
en el contrato. El tiempo de cooldown se puede modificar si el contrato ya ha sido lanzado.
