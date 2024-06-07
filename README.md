# Megacamp-Quickstart

> [!IMPORTANT]
> **Estas son las instrucciones de los requerimientos previos a nuestro bootcamp. En el caso que no tengan instalado todo esto, no podrán participar apropiadamente del bootcamp.**

## Los requerimientos:

1. Independientemente de cual sea el sistema operativo que uses (linux, windows o macOS) tenemos una guía para ti, queremos facilitarte tu camino al aprendizaje, así que no te preocupes.

### IDEs

> [!TIP]
> Sugerimos que uses un IDE, el cual se te sea amigable y comodo, buenas alternativas son

- [VsCode](https://code.visualstudio.com/Download)
- Otra muy buena alternativa que puedes utilizar es [Sublime Text](https://www.sublimetext.com/)
- No olvidemos a [zed](https://zed.dev/) que es un muy buen IDE para MacOS.
- En el caso de que seas un usuario más experimentado, utilizes alguna distro de MacOS o Linux y quieras más control sobre tu entorno te recomiendo probar [Neovim](https://neovim.io/) con su ecosistema de plugins basado en [Lua](https://lua.org/) al que puedes acceder mediante [Lazy Nvim](https://github.com/folke/lazy.nvim) .

### Git y Github

> [!NOTE]
> Durante todas nuestras sesiones, utilizaremos GitHub y su herramienta de CLI, git. Este es un indispensable en la industria del desarrollo de software. A continuación, las guías de instalación para cada sistema operativo:

#### Para Windows

- Descarga [git](https://www.git-scm.com/download/win) desde la pagina oficial

#### Para Linux

- Descarga git desde la terminal

```bash
# para Debian/Ubuntu
sudo apt-get install git

# para Fedora
sudo dnf install git

# para CentOS
sudo yum install git

# para Arch Linux
sudo pacman -S git

```

Luego verifica la instalación utilizando este comando en la terminal:

```bash
git --version
```

#### Para MacOs

1. Abre el terminal, usualmente está dentro de Apps/Utilities

2. Verifica si git está instalado utilizando

```bash
git --version

```

3. En el caso de que no esté instalado ejecuta:

```bash
xcode-select --install
```

4. Vuelve a verificar y listo!

### Node.JS

> [!IMPORTANT]
> Una herramienta indispensable para poder desarrollar aplicaciones web de toda medida es [Node.JS](https://nodejs.org/en) y lo utilizaremos en conjunto con [hardhat](https://hardhat.org/hardhat-runner/docs/getting-started) para desarrollar smart contracts.

#### Para Windows

1. Descarga el instalador de Node.JS [aqui!](https://nodejs.org/en/download/prebuilt-installer)
2. Instalalo y listo!

#### Para Linux

1. Ejecuta lo siguiente en el terminal:

```bash
# installs nvm (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

# download and install Node.js (you may need to restart the terminal)
nvm install 20

# verifies the right Node.js version is in the environment
node -v # should print `v20.14.0`

# verifies the right NPM version is in the environment
npm -v # should print `10.7.0`
```

2. y listo!!

#### Para MacOS

1. Abre tu terminal

2. Ejecuta esto dentro de ella:

```bash
# installs nvm (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

# download and install Node.js (you may need to restart the terminal)
nvm install 20

# verifies the right Node.js version is in the environment
node -v # should print `v20.14.0`

# verifies the right NPM version is in the environment
npm -v # should print `10.7.0`
```

3. y listo!

> [!NOTE]
> Asegúrate de seguir cada guía paso a paso para tener todo listo antes de comenzar el bootcamp. Si tienes alguna duda o encuentras problemas durante la instalación, no dudes en contactarnos para recibir ayuda. ¡Estamos aquí para apoyarte en tu camino al aprendizaje!
