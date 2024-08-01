# Como baixar o Linux no Windows

Nós podemos usar o [WSL](https://learn.microsoft.com/pt-br/windows/wsl/install) para executar o Linux dentro do seu windows.

# O que faz o WSL?

Basicamente, o wsl cria um [container](https://www.redhat.com/pt-br/topics/containers) no seu windows que possibilita você baixar distribuicões do Linux como o Ubuntu, PopOS, Manjaro e muitas outras.

O WSL é muito útil para quem é desenvolvedor e precisa da facilidade do Linux para baixar pacotes e executar comandos na linha de comando.

# Como instalar o WSL?

Para baixar o wsl, você pode acessar o [site](https://learn.microsoft.com/pt-br/windows/wsl/install) e executar os passos da documentacão.

Para inicializar a instalacão você precisa executar o cmd do windows como administrador.

Para fazer isso, aperte o botão do windows no seu teclado e procure por **cmd**.

Após isso, clique em cima do **cmd** com o botão direito do mouse e selecione **Executar como administrador**.

Pronto, seu cmd tem permissão de administrador e agora você pode prosseguir com a sua instalacão.

# Comando de instalacão do WSL

Execute o comando abaixo para inicializar a instalacão, após o processo de instalacão será necessário **reiniciar** seu computador.
```shell
wsl --install
```

Este comando irá instalar as dependencias do WSL para executar o Linux no seu computador windows, além disso, irá baixar a distribuicão do Linux [Ubuntu](https://ubuntu.com/).

# Próximos passos

Agora chega o momento em que precisamos configurar o Linux, mas podemos deixar isso para próxima [aula](./docs/configurando-linux.md).
