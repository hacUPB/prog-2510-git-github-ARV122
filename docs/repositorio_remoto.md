para crear un repositorio remoto en github es sencillo solo hay que seguir los siguientes pasos 
Ve a GitHub e inicia sesión.
En la esquina superior derecha, haz clic en el ícono "+" y selecciona "New repository".
Escribe un nombre para tu repositorio (ejemplo: mi-repositorio).
Elige si quieres que sea Público o Privado.
No marques la opción "Add a README", ya que Git te pedirá que hagas el primer push desde tu repositorio local.
Haz clic en "Crear repositorio".

el github te mostrara una URL la cual es del repositorio remto 

aqui unos comandos que se pueden utilizar 
# 1. Inicializar el repositorio local (si no está creado)
mkdir mi-repositorio
cd mi-repositorio
git init

# 2. Crear un archivo de prueba
echo "# Mi Repositorio" > README.md

# 3. Agregar y confirmar cambios
git add .
git commit -m "Primer commit"

# 4. Vincular con GitHub
git remote add origin https://github.com/tu-usuario/mi-repositorio.git
git remote -v  # Verifica la conexión

# 5. Subir los cambios a GitHub
git push -u origin main  # O usa 'master' si tu repositorio está en esa rama
