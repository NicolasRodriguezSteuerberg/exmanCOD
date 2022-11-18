# examenDAM
Para utilizarlo en el examen
1 ejercicio, clonado
Para clonar el repositorio, copie el codigo del repositorio, seguido de esto, abrí la terminal, en mi caso me dirigí a documentos con cd Documentos, cree una carpeta examen con el comando mkdir examen. Despues de esto clone el repositorio del profe con git clone https://github.com/damiancastelao/examenDAM.git
2 ejercicio, crear repositorio
Ahora que está clonado,creo un repositorio nuevo. Al crearlo, copio el codigo, entonces en la terminal pongo git init. Al haber un remote origin, lo borro para que sea el mio con git remote rm origin. Seguido de esto ya puedo hacer mi git remote add origin https://github.com/NicolasRodriguezSteuerberg/exmanCOD.git. Despues de hacer esto modifico el README.md añadiendo los pasos del 1 y 2 ejercicio con echo texto >> README.md. Al finalizar esto hago git add README.md, git commit -m primerCommitExamen, por ultimo subo el cambio con git push -u origin main
3 ejercicio
Para este ejercicio cogí el boletin 8_6 de programació, lo copie y pegué en la carpeta examenDAM. Seguido de esto cree un .gitignore en lo que escribe dentro lo siguiente:
/nbproject/
/out/
/.idea/
/Boletin8_6.iml/
/build.xml/
/manifest.mf/
Para cambiar el autor del commit realicé lo siguiente git config --global user.name FalsificadorDeDamian 
Para subir los cambios puse:
git add .
git commit -m 3ejercicio
