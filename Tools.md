# Comandos para ajudar no Linux

- Aqui estarão listados alguns comandos shell que podem ajudar alguém que está começando agora a usar o Linux, qualquer contribuição será bem vinda 😁

## Atualizar tudo

  ```shell

    sudo apt update && sudo apt full-upgrade -y && sudo apt autoremove -y && sudo apt autoclean && sudo snap refresh
  ```

## Bug da att Snap-Store (Ubuntu && Fedora)

- Desative a snap store com o comando :

    ```shell
    sudo killall snap-store
    ```
  
- Faça o comando de att snap
  
    ```shell
    sudo snap refresh
    ```
