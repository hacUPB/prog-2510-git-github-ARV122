para crear un repositorio local con comandos git podemos aplicar lo conocido en clase que seria los siguientes pasos 
cd C:/ruta/del/proyecto     # Moverse a la carpeta donde se quiere crear el repositorio
mkdir MiProyecto && cd MiProyecto  # Crear la carpeta y entrar en ella
git init                    # Inicializar el repositorio Git
echo "# Mi Proyecto" > README.md  # Crear un archivo de prueba
git add .                    # Agregar archivos al área de preparación
git commit -m "Primer commit" # Guardar los cambios en el repositorio local
git status                   # Verificar el estado del repositorio
git log --oneline            # Ver historial de commits

con estos pasos podriamos crear el repositorio local con los comandos de git 