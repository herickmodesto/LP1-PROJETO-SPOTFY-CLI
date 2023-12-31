# GERENCIADOR DE MÚSICAS E PLAYLISTS
## Discente
| Nome        | Matricula   |
| ----------- | ----------- |
| Herick Modesto Ciriaco      | 20220028409       |
## O que é?
<hr/>

O projeto se trata de uma CLI(Comand line interface), totalmente programada em C++, que oferece ferramentas pare gerenciamento de "músicas" e "playlists", com o intuito de aprender a implementar o conceito de Manipulação de Arquivos, lista encadeada e herança. Esse projeto faz parte da terceira unidade da matéria LP1(Liguagem de programação 1) do curso BTI(Bacharelado em tecnologia da informação) da UFRN(Universidade federal do Rio Grande do Norte).

## Compilar o projeto
<hr/>

Para compilar o projeto basta instalar o cmake, após a instalação execute o seguinte comando no terminal:

~~~bash
cmake ./CMakeLists.txt
~~~
Esse comando irá gerar um arquivo Makefile no diretório raiz do projeto. Então ao executar:
~~~bash
make
~~~
O projeto será combilado e um arquivo chamado **spotfy_cli** será gerado automaticamente.
## Estruturas de pastas
<hr/>

O projeto contém duas pastas relevantes, a pasta **src/** que contem os arquivos de implementação e **include/** que contém os arquivos de definição.
```c++
src
├── DisplayMenus.cpp
├── Main.cpp
├── Menu.cpp
├── Music.cpp
├── MusicsManager.cpp
├── Playlist.cpp
├── PlaylistManager.cpp
├── PlaylistMusicsManager.cpp
└── TerminalColors.cpp
```

```c++
include/
├── Definitions.hpp
├── DisplayMenus.hpp
├── ListaEncadeada
│   ├── List.hpp
│   └── Node.hpp
├── Menu.hpp
├── Music.hpp
├── MusicManager.hpp
├── Playlist.hpp
├── PlaylistManager.hpp
├── PlaylistMusicsManager.hpp
└── TerminalColors.hpp
```
## Menus do projeto

### Menu principal
![alt](./assets/main_menu.png)

### Menu de músicas
![alt](./assets/music_menu.png)

### Menu de playlists
![alt](./assets/playlists_menu.png)

### Menu de músicas de uma playlist
![alt](./assets/playlist_musics_menu.png)
