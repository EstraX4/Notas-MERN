## TypeScript

Como resumen, el comando `npx tsc --init` inicializa un archivo `tsconfig.ts`. En este va estar la configuración como el target, ourDir, strictMode, etc. Evitándonos tener que poner esas flags en cada compilación.  
.  
Una vez con ese archivo, solo corremos el comando `npx tsc` y listo.  
.  
Y ya por ultimo, podemos evitarnos la compilación continua corriendo el comando `npx tsc --watch`