# examenDAM
Para utilizarlo en el examen
1 ejercicio, clonado
Para clonar el repositorio, copie el codigo del repositorio, seguido de esto, abrí la terminal, en mi caso me dirigí a documentos con cd Documentos, cree una carpeta examen con el comando mkdir examen. Despues de esto clone el repositorio del profe con git clone https://github.com/damiancastelao/examenDAM.git
2 ejercicio, crear repositorio
Ahora que está clonado,creo un repositorio nuevo. Al crearlo, copio el codigo, entonces en la terminal pongo git init. Al haber un remote origin, lo borro para que sea el mio con git remote rm origin. Seguido de esto ya puedo hacer mi git remote add origin https://github.com/NicolasRodriguezSteuerberg/exmanCOD.git. Despues de hacer esto modifico el README.md añadiendo los pasos del 1 y 2 ejercicio con echo texto >> README.md. Al finalizar esto hago git add README.md, git commit -m primerCommitExamen, por ultimo subo el cambio con git push -u origin main
