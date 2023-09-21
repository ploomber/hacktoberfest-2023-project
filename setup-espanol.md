# Instrucciones de configuración

## :hammer_and_wrench: Herramientas que utilizaremos

Trabajaremos con:

1. git: A través de GitHub Desktop y la línea de comandos para asegurarnos de que podamos colaborar en el código.
2. conda y poetry: Para gestionar nuestros entornos Python.
3. Virtual Studio Code (VSCode): Para escribir nuestro código.
4. Paquetes de código abierto: Ploomber, JupySQL, Jupyter notebooks, FastAPI, Haystack y Chainlit.
5. Docker: Para contenerizar nuestras aplicaciones.

## :rocket: Software para instalar

Revisa las instrucciones de configuración del entorno para el entorno local que usarás en este curso.

<details>
<summary> Instalar GitHub Desktop</summary>
Fuente: https://desktop.github.com/

Haz clic en el botón Descargar para {OS}.

</details>

<details>
<summary>Configuración de Github SSH (si estás usando Git desde la terminal en lugar de GitHub Desktop)</summary>
El Protocolo de Shell Seguro (SSH) proporciona un canal de comunicación seguro en una red no segura. ¡Configurémoslo!
<p></p>
1. Genera un par de claves SSH privada/pública.

```bash
ssh-keygen -o -t rsa -C "tu dirección de correo electrónico para github"
```

2. Guarda el par de archivos. ¡La ubicación predeterminada ~/.ssh/id_rsa está bien!

3. En el indicador, escribe una frase de contraseña segura.

4. Copia el contenido de la clave pública que compartiremos con GitHub.

    * Mac: `pbcopy < ~/.ssh/id_rsa.pub``

    * Windows (WSL): `clip.exe < ~/.ssh/id_rsa.pub`

    * Linux: `xclip -sel c < ~/.ssh/id_rsa.pub`

5. Ve a tu cuenta de GitHub y ve a Configuración.

6. Bajo Acceso, haz clic en la pestaña SSH y claves GPG a la izquierda.

![image](https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/5fb54f16-7279-49c4-bda3-2da36cbbc306)

7. Haz clic en el botón Nueva clave SSH.

![image](https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/d5551c28-9d70-438c-b45d-43698384e3ff)

8. Nombra la clave y pega la clave pública que copiaste. Haz clic en el botón Agregar clave SSH.

![image](https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/8f7c4496-0e88-4058-9baf-73495322db8b)

</details>

<details>
<summary>Instalar miniconda</summary>
Fuente: https://docs.conda.io/projects/miniconda/en/latest/#id2

Elige la distribución que tenga sentido para tu sistema operativo.
</details>

<details>
<summary>Instalar y configurar VSCode</summary>
Fuente: https://code.visualstudio.com/docs/setup/setup-overview

Elige la distribución que tenga sentido para tu sistema operativo.

<summary>Instalar las extensiones de Python y Jupyter Notebook</summary>
Haz clic en la pestaña Extensiones <img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/f17d8f45-f174-4b9b-be92-8f1e85d8a77b" width=30px/>.

Escribe "Python" en la barra de búsqueda.

Haz clic en Instalar <img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/4c06f2a7-d7c3-4c59-b656-82170518cbeb" width=30px/> tanto en la <ins><strong>Extensión de Python</strong></ins> como en la <ins><strong>Extensión de Cuaderno Jupyter de Microsoft</strong></ins>.

</details>
<p> </p>
