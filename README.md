# Hello World (bash, Ubuntu)

Aplicación **muy sencilla** en `bash` que imprime `hello world`.

Contenido principal:

- `hello-world.sh`: script que imprime `hello world`.

## Uso en Ubuntu / EC2 (Ubuntu)

1. Sitúate en la carpeta del proyecto (por ejemplo si la copiaste a `/home/ubuntu/script-project`):

```bash
cd /home/ubuntu/script-project
```

2. Dale permisos de ejecución al script (solo la primera vez):

```bash
chmod +x hello-world.sh
```

3. Ejecútalo:

```bash
./hello-world.sh
```

Verás en pantalla:

```text
hello world
```

## Si subes el proyecto a Git

1. En tu PC, dentro de `script-project`, inicializa git y sube a GitHub/GitLab.
2. En tu instancia EC2 Ubuntu:
   ```bash
   sudo apt update
   sudo apt install -y git
   git clone <URL_DE_TU_REPO>.git
   cd script-project
   chmod +x hello-world.sh
   ./hello-world.sh
   ```

# workspace
