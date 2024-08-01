# Como configurar o Linux após a instalacão do WSL

Como mencionamos anteriormente, a distribuicão instalada foi o [Ubuntu](https://ubuntu.com/).

O Ubuntu possui algumas funcionalidades bem diferentes, uma delas é o gerenciador de pacotes do próprio Ubuntu, o **[APT ou melhor, Advanced Package Tool](https://ubuntu.com/server/docs/package-management)**

# Configurando seu sistema operacional Linux (Ubuntu)

Após a execucão do comando **wsl --install**, será necessário reiniciar seu computador para iniciar a configuracão.

Quando você logar novamente em seu computador, você pode procurar no windows por **ubuntu** na barra de pesquisa do windows (só precisa apertar a tecla do windows e digitar ubuntu para isso).

Você deve encontrar uma opcão chamada Ubuntu após essa pesquisa e clicar nela, isso vai abrir um terminal para você.

Será necessário esperar alguns minutos para o Linux inicializar, lembre-se de esperar o tempo necessário para isso, pode demorar um pouco.

# Inicializando o Linux

Com o terminal do Ubuntu aberto, o Linux irá pedir para você digitar um nome de usuário.

```shell
Enter new UNIX username:
```

Digite o nome do seu usuário. Em seguida, irá pedir uma senha para você.

**OBSERVACÃO: nesta etapa, é normal não visualizar o que você digitou na sua senha, então certifique-se tenha digitado direito sua senha.**

```shell
New password:
Retype new password:
```

Pronto, seu usuário e senha está configurado.

# Conhecendo o gerenciador de pacotes APT

O gerenciador de pacotes, nada mais é do que um instalador nativo da distribuicão, se você tiver familiaridade com Python, provavelmente já escutou falar sobre o **pip** o gerenciador de pacotes do Python.

O objetivo é o mesmo, baixar dependencias e aplicacões através da linha de comando.


O APT acompanha alguns comandos para executar na linha de comando.

O Linux possui um **super usuário** e nós chamamos ele de root, a maioria das operacões de instalacão precisam ser executadas com a permissão de root, para isso nós utilizamos o **sudo** no inicio dos comandos.

## Atualizar pacotes 
```shell
sudo apt update
```

## Instalar um pacote
```shell
sudo apt install nome_do_pacote
```

## Remover um pacote
```shell
sudo apt remove nome_do_pacote
```

## Atualizar todos os pacotes instalados para uma versão mais recente
```shell
sudo apt upgrade
```

## Remover pacotes que foram instalados como dependências de outros pacotes e que não são mais usados

```shell
sudo apt autoremove
```

# Próximos passos

Com o seu usuário e senha configurado, podemos cobrir alguns comandos básicos do linux na próxima [aula](./docs/comandos-linux.md)

