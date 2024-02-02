# Readme
        
### El ejercicio lo he realizado con la interfaz gráfica del IntelliG tal y como nos indicaste en clase, de todas formas como nos pides un Readme.md con los comandos, te dejo aquí los comandos que necesitariamos para hacer la actividad si la quisieramos hacer por consola.
        
Git init  
git add Main  
git commit -m "commit a"  
git commit -m "commit b"  
git branch Lider  
git checkout Lider  
git add Lider  
git commit -m "commit L1"  
git commit -m "commit L2"  
git commit -m "commit L3"  
git checkout main  
git merge --squash Lider  
  
### Imagen Rama Main
![ramamain](https://github.com/Adriandam1/Merge-squash/assets/72071798/89b8aea4-8eb9-4e2c-8e35-6b22defcee77)

### Imagen Rama Lider
![ramalider](https://github.com/Adriandam1/Merge-squash/assets/72071798/94950e26-6502-427e-9208-14c6b802cad9)  

mas tarde durante la clase indicaste que querias 2 merge squash asi que ahora hago otro del main a la lider:  
git commit -m "commit post1"  
git commit -m "commit post2"  
git commit -m "commit post3"
git checkout Lider  
git merge --squash main  

### Imagen Rama Main 2
![ramamain2](https://github.com/Adriandam1/Merge-squash/assets/72071798/a0c3e09f-c25c-49f0-924d-531d97b12858)  

### Imagen Lider Main 2  
![ramalider2](https://github.com/Adriandam1/Merge-squash/assets/72071798/87296a2a-5b8c-4309-82de-b865b7732de5)


